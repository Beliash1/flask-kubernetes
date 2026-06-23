# Flask Kubernetes Demo

A simple Flask application deployed on Kubernetes using Docker and Minikube.

## Technologies

- Python Flask
- Docker
- Kubernetes
- Minikube
- YAML

## Run with Docker

```bash
docker build -t flask-k8s:v1 .
docker run -p 5000:5000 flask-k8s:v1
```

## Deploy to Kubernetes

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

## Verify

```bash
kubectl get deployments
kubectl get pods
kubectl get services
```
