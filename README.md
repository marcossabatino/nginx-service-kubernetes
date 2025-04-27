# 🚀 Kubernetes: Deploying and Exposing Nginx Service

This project demonstrates how to **deploy an Nginx server** on Kubernetes using **Minikube**, and **expose it externally** via a NodePort Service.

---

## 📋 Project Overview

- **Deployment**: Nginx
- **Replicas**: 3
- **Service**: NodePort (accessible outside the cluster)


## 🛠️ Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/) installed and configured
- [kubectl](https://kubernetes.io/docs/tasks/tools/) installed
- Basic understanding of Kubernetes concepts


📂 Project Structure
.
├── nginx-deployment.yaml
├── nginx-service.yaml
└── README.md


## 🏗️ Full Setup Steps

### 1. Start Minikube
Run:
```bash
minikube start

### 2. Create and Apply the Deployment
kubectl apply -f nginx-deployment.yaml

### 3. Create and Apply the Service
kubectl apply -f nginx-service.yaml

### 4. Access the Nginx Server
minikube ip
Access http://<minikube-ip>:<node-port>

