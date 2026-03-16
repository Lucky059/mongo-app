# MongoDB + Mongo Express on Kubernetes

##  Overview
This project shows how I containerized and deployed **MongoDB** and **Mongo Express** using **Kubernetes**.  
MongoDB acts as the database, while Mongo Express provides a web interface to manage MongoDB collections.

---

## 🛠️ Tools & Technologies
- **Docker** – container images for MongoDB and Mongo Express
- **Kubernetes** – orchestration platform
- **kubectl** – CLI for managing Kubernetes resources
- **Minikube** – local Kubernetes cluster
- **ConfigMap & Secret** – configuration and credentials management


mongo-app/
├── configmap.yaml             # Non-sensitive configuration
├── mongodb-deployment.yaml    # MongoDB Deployment + Service
├── mongoexpress.yaml          # Mongo Express Deployment + Service
├── .gitignore                 # Ensures secrets are not committed
└── mongosecret.yaml           # ⚠️ Local only, excluded from Git

