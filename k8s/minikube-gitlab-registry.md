`minikube ssh`
```
echo "192.168.49.1 gitlab.local" | sudo tee -a /etc/hosts
```

```
minikube start --insecure-registry="gitlab.local:5050"
```