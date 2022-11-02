## **Run** without Docker and Kubenetes

```console
npm start
```
 
 ## **Build** with Dockerfile

```console
docker build -t k8s_node_helloworld k8s_helloworld
```

## **Run** with Docker-compose 

```console
docker-compose up
```

## **Run** with Kubernetes

Run minikube
```console
minikube start
```

Run application with kubernetes
```console
kubectl apply -f development.yaml
kubectl apply -f service.yaml
```

Show result
```console
minikube service k8s-web-hello-service
```
