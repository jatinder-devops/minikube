# 02 - Kubernetes Architecture

A Kubernetes cluster has a Control Plane and Worker Nodes.

## Control Plane
- API Server: Entry point for Kubernetes API requests.
- etcd: Stores cluster state and configuration.
- Scheduler: Selects nodes for new Pods.
- Controller Manager: Runs controllers that maintain desired state.

## Worker Node
- Kubelet: Ensures assigned Pods are running.
- Container Runtime: Runs containers, such as containerd.
- kube-proxy: Implements Service networking rules where used.

## Request Flow
1. User submits a manifest using kubectl.
2. API Server validates the request.
3. Cluster state is stored in etcd.
4. Scheduler selects a suitable node.
5. Kubelet asks the container runtime to run the Pod.

## Commands
```bash
kubectl get nodes
kubectl get pods -n kube-system
kubectl describe node
```

## Assignment
1. Explain API Server and etcd.
2. What does Scheduler do?
3. Explain Kubelet.
4. Draw Kubernetes architecture.
