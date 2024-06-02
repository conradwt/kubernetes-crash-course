# Labs - Deploying Voting App on Kubernetes

## Create Resources

```zsh
kubectl create namespace vote
kubectl apply -f labs/deploying-voting-app-on-kubernetes -n vote
```

## Delete Resources

```zsh
kubectl delete -f labs/deploying-voting-app-on-kubernetes -n vote
kubectl delete namespace vote
```
