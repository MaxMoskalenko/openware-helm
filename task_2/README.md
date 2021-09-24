```
minikube start
helm install -f values.yaml next-stable .
minikube service next-webapp --url -n next-webapp-namespace
```