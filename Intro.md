# 01 - Introduction to Kubernetes

## What is Kubernetes?
Kubernetes (K8s) is an open-source container orchestration platform. It automates deployment, scaling and management of containerized applications.

## Why Kubernetes?
- Automates container deployment.
- Restarts failed containers.
- Scales applications.
- Provides service discovery and load balancing.
- Supports rolling updates and rollbacks.

## Important Terms
- Cluster: A group of machines managed by Kubernetes.
- Node: A machine in a cluster.
- Pod: The smallest deployable Kubernetes unit.
- Deployment: Manages replicated Pods.
- Service: Provides stable network access to Pods.

## Docker vs Kubernetes
Docker builds and runs containers. Kubernetes manages containerized applications across a cluster.

## Commands
```bash
kubectl version
kubectl cluster-info
kubectl get nodes
kubectl get pods -A
```

## Assignment
1. Explain Kubernetes in your own words.
2. Why do companies use Kubernetes?
3. Explain the difference between Docker and Kubernetes.
4. What is a Pod?
