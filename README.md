# Task 5 - Build a Kubernetes Cluster Locally with Minikube

## 📌 Objective
The goal of this task is to deploy and manage applications in a Kubernetes cluster running locally on AWS EC2 using Minikube.

---

## 🛠 Tools Used
- **Minikube** - To create a single-node Kubernetes cluster locally
- **kubectl** - To interact with the Kubernetes cluster
- **Docker** - As the container runtime
- **AWS EC2 (Ubuntu 24.04)** - Cloud instance to host Minikube

---

## 🚀 Steps Performed

### 1️⃣ Environment Setup
1. **Install Docker**
   ```bash
   sudo apt-get update
   sudo apt-get install -y docker.io
   sudo usermod -aG docker $USER
   newgrp docker
   docker --version
