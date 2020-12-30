# k8s-redis

在config.yaml文件中添加了redis的配置信息，可以自行设置

在pv.yaml文件中添加了nfs的数据挂载，如果不需要挂载的话可以不使用该文件，同时需要删除redis.yaml文件中的挂载路径
