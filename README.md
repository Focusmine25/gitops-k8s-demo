# GitOps-K8s-Demo

## Overview
This project demonstrates a GitOps workflow with **ArgoCD** on a local **Minikube** cluster. All Kubernetes manifests live in the `k8s/` folder. ArgoCD watches the repository and applies changes automatically.

## Setup

1️⃣ Start Minikube:
```bash
minikube start --driver=docker --cpus=2 --memory=3072
