# k8s cluster for portfolio

using eksctl


```shell script
# create cluster with 2 worker node
eksctl create cluster -f cluster.yaml
```


```shell script
# delete cluster
eksctl delete cluster -f cluster.yaml
```