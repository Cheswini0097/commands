Command to check the  Kubectl version

```
kubectl version
```
Command to check eksctl version

```
eksctl version
```

Command to run cluster setup file 

```
eksctl create cluster --config-file=eks.yaml
```

Command to run the Kubectl file

```
kubectl apply -f <filename>
```
Command to login into running pod:

```
kubectl exec -it nginx bash
```

Command to check the Namespaces:

```
kubectl get namespaces
```

Command to get replica sets.

```
kubectl get replicasts
```

command to check the storage class

```

kubectl get sc
```


Command to login in to container

```
kubectl exec -it mysql-6d8878f8f4-244md -n expense -- bash
```

