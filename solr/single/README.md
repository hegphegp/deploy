## 其实是因为默认solr/home位置不对。让它指向solr-5.5.0/server/solr就行了，找到web.xml中的
```
<env-entry>
   <env-entry-name>solr/home</env-entry-name>
   <env-entry-value>/${安装目录}/solr5.5.0/server/solr</env-entry-value>
   <env-entry-type>java.lang.String</env-entry-type>
</env-entry>
```