```
minikube start
kubectl apply -f argocd/argocd-ns.yaml
kubectl apply -f argocd/argocd.yaml --namespace argocd
kubectl apply -f argocd/appproj-cluster-project.yaml --namespace argocd
```