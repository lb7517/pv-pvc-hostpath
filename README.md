#### PV-PVC

* * *
pv全称PersistentVolume，即持久卷
pvc全称PersistentVolumeClaim，即持久卷申请


* * *
**注意:**
1. pv中定义的storage存储大小一定要大于pvc中申请的storage大，才能被匹配上
2. pv使用**hostpath类型的持久卷**时，多节点集群中，注意要在pod运行的节点上建立hostpath需要的目录或者文件