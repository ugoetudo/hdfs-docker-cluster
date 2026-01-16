# Simple HDFS Cluster Deployment Using Docker

In ```docker-compose.yml``` (Source: [Dirk Steynberg](https://bytemedirk.medium.com/setting-up-an-hdfs-cluster-with-docker-compose-a-step-by-step-guide-4541cd15b168)) we define a namenode and two datanodes. The yml file also defines how we map container volumes and bind our host's ```hadoop_config``` to the appropriate locations on the hdfs image used to define each node in the cluster. 

Docker compose requires that you install Docker Desktop on Windows and Mac - although this needn't be the case in WSL - I will test this and update :smile: 