1. create a cluster

```
    gcloud container clusters create k8s \
    
    --cluster-version 1.16.8-gke.15 \ 
    --zone asia-northeast1-a \ 
    --num-nodes 3 \ 
    --machine-type n1-standard-4 \ 
    --enable-network-policy \ 
    --enable-vertical-pod-autoscaling
```

EX. get available cluster versions

```
    gcloud container get-server-config
```

2. get credential

```
    gcloud container clusters get-credentials k8s --zone asia-northeast1-a
```

3. attach privledges to a user

```
kubectl create clusterrolebinding user-cluster-admin-binding --clusterrole=cluster-admin --user=USER@gmail.com
```


4. confirm client and cluster versions

```
    kubectl version
```

