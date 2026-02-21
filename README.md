# 🚀 Three-Tier Application Deployment on Kubernetes (Minikube)

## 📌 Project Overview

This project demonstrates deployment of a **3-tier cloud-native application** on Kubernetes using:

- Docker
- Minikube
- Kubernetes
- MySQL
- Node.js (Express)
- ConfigMap
- Secret
- PersistentVolumeClaim
- NodePort Service

---

## 🏗 Architecture

Frontend (Future Extension)
        ↓
Backend (Node.js)
        ↓
MySQL (Persistent Storage)

Kubernetes Components Used:

- Namespace
- Deployment
- Service (ClusterIP & NodePort)
- Secret
- ConfigMap
- PVC

---

## 🖥️ Environment Requirements

Minimum VM Specs:

- 2 vCPU
- 4GB RAM
- 20GB Disk
- Ubuntu 22.04 / 24.04

---

## 🔧 Installation Steps

### 1️⃣ Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl enable docker
sudo systemctl start docker
sudo usermod -aG docker $USER
