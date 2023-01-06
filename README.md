# kubernetes-configuration
Configuration for running rqlite on Kubernetes. Full documentation on running rqlite on Kubernetes is available [here](https://rqlite.io/docs/guides/kubernetes/).

## Create a 3-node cluster
```bash
kubectl apply -f service.yaml
kubectl apply -f statefulset-3-node.yaml
```
