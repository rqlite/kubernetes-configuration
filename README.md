# kubernetes-configuration
Configuration for running rqlite on Kubernetes. Full documentation on running rqlite on Kubernetes is available [here](https://rqlite.io/docs/guides/kubernetes/).

Alternatively you may wish to use the [rqlite Helm charts](https://github.com/rqlite/helm-charts).

## Create a 3-node cluster
```bash
kubectl apply -f service.yaml
kubectl apply -f statefulset-3-node.yaml
```
