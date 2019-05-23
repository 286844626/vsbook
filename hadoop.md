# hadoop

1. java
2. ssh
3. 主机名、映射文件
4. 配置文件
5. 初始化
6. jps

> hadoop配置文件
```
hadoop-env.sh、yarn-env.sh    #添加java路径
slaves        #从机名
core-site.xml 
    fs.defaultFS    hdfs://主机名:端口号(9000)   #namenode缺省地址
    hadoop.tmp.dir    hadoop_home/tmp   #hadoop运行时文件存储路径
hdfs-site.xml
    dfs.replicaion  3   #副本数
    dfs.name.dir    路径
    dfs.data.dir    路径
mapred-site.xml
    mapreduce.framework.name    yarn
yarn-site.xml
    yarn.resourcemanager.hostname   主机名
    yarn.resourcemanager.aux-services   mapreduce_shuffle
```
> hdfs namenode -format