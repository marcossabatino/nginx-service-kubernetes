# 🚀 Kubernetes Nginx Deployment and Service

Welcome! This project demonstrates how to deploy an **Nginx** server on Kubernetes using **Minikube**, and expose it as a service for external access.

## 📋 Project Overview

- **Deployment**: Nginx server
- **Replicas**: 3
- **Service**: Exposed via **NodePort**

This is a perfect hands-on example for practicing basic Kubernetes objects like Deployments and Services.

---

## 🛠️ Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/) installed and running
- [kubectl](https://kubernetes.io/docs/tasks/tools/) CLI installed
- Basic knowledge of Kubernetes concepts

---

## 🏗️ Steps to Deploy

### 1. Start Minikube

```bash
minikube start
