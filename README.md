## Start minkube
```
minikube start --driver docker
```

## Install argocd
```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
kubectl apply -n argocd -f clusters/mk-work/infrastructure
```
