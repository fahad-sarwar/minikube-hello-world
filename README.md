
# minikube-hello-world

https://itsmetommy.com/2018/03/30/kubernetes-learning-with-minikube/

## Setup
Following command looks for all yaml files within the current directory and runs the

```
kubectl create -f .
```

Get services.

```
kubectl get services
```

Launch browser.

```
minikube service itsmetommy-service
```

Clean up

```
kubectl delete -f .
```