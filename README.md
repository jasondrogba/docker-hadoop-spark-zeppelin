# docker-hadoop-spark-zeppelin
快速简易搭建2节点hadoop+spark集群，使用zeppelin交互式开发

第一步先下载项目

第二步启动集群

```
cd docker-hadoop-spark-zeppelin

docker-compose up -d
```

# 服务端口设置

namenode:<IP_address>:9870

datanode1:<IP_address>:9864

datanode2:<IP_address>:9863

resource manager:<IP_address>:8088

history server:<IP_address>:8188

nodemanager:<IP_address>:8042

spark master:<IP_address>:8080

zeppelin:<IP_address>:80

# 各服务版本

hadoop_version:3.2.1

spark_version:3.1.1

zeppelin_version:0.8.0
