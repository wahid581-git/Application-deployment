# 🚀 Brain Tasks App - DevOps Deployment

## 📌 Project Overview

This project demonstrates an end-to-end CI/CD pipeline to deploy a React application into a production-ready environment using AWS services.

---

## 🧠 Architecture

GitHub → CodePipeline → CodeBuild → Docker → Amazon ECR → Amazon EKS → LoadBalancer → User

---

## ⚙️ Technologies Used

* AWS CodePipeline
* AWS CodeBuild
* Amazon ECR
* Amazon EKS
* Docker
* Kubernetes
* GitHub

---

## 🐳 Dockerization

* Created a Dockerfile to containerize the React application
* Built Docker image locally
* Pushed image to Amazon ECR

---

## ☸️ Kubernetes Deployment

* **Deployment.yaml** → Manages application pods
* **Service.yaml** → Exposes application via LoadBalancer

---

## 🔁 CI/CD Pipeline Flow

1. Code pushed to GitHub
2. CodePipeline triggers automatically
3. CodeBuild builds Docker image
4. Image pushed to ECR
5. EKS deploys updated application

---

## 📸 Screenshots

### 🔹 CodePipeline Success

![Pipeline](screenshots/pipeline.png)

### 🔹 ECR Repository

![ECR](screenshots/ecr.png)

### 🔹 EKS Nodes

![EKS](screenshots/eks-nodes.png)

### 🔹 Application Running

![App](screenshots/app.png)

---

## 🌐 Application Access

http://<your-loadbalancer-url>

---

## ⚠️ Challenges Faced

* IAM permission errors
* ECR authentication issues
* VPC configuration problems
* Pods stuck in Pending state
* Port mismatch (3000 vs 80)
* LoadBalancer exposure issues

---

## ✅ Conclusion

Successfully implemented a CI/CD pipeline to automate the build, containerization, and deployment of a React application on AWS EKS.
