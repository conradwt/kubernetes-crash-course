# KodeKloud - Kubernetes Crash Course

## Labs - Deploying Voting App on Kubernetes

1. create resources

   ```zsh
   kubectl create namespace vote
   kubectl apply -f labs/deploying-voting-app-on-kubernetes -n vote
   ```

2. delete resources

   ```zsh
   kubectl delete -f labs/deploying-voting-app-on-kubernetes -n vote
   kubectl delete namespace vote
   ```
