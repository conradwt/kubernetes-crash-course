# Labs - Deploying Voting App on Kubernetes

## Create Resources

```zsh
kubectl create namespace vote
kubectl apply -f vote-app -n vote
```

## Delete Resources

```zsh
kubectl delete -f vote-app -n vote
kubectl delete namespace vote
```
