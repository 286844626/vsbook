# sparkHA

> 前置条件 hadoop、scala、java

## 修改配置文件spark-env.sh
```
export JAVA_HOME=java_home
export SCALA_HOME=scala_home
export HADOOP_HOME=hadoop_home
export SPARK_MASTER_IP=master     #主节点ip或映射名
export SPARK_MASTER_HOST=master #主节点
export SPARK_LOCAL_IP=slave1 #当前节点ip或映射名
export SPARK_WORKER_MEMORY=1G

```