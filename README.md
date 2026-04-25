Brain Tasks App - DevOps Deployment
📌 Project Overview

This project demonstrates a complete CI/CD pipeline using AWS services to deploy a containerized application on Kubernetes (EKS).

🧠 Architecture

GitHub → CodePipeline → CodeBuild → Docker → ECR → EKS → LoadBalancer → User

⚙️ Technologies Used
AWS CodePipeline
AWS CodeBuild
Amazon ECR
Amazon EKS
Docker
Kubernetes
GitHub
🐳 Docker Implementation
Application containerized using Docker
Image built using Dockerfile
Image pushed to Amazon ECR
☸️ Kubernetes Deployment
Deployment.yaml → manages pods
Service.yaml → exposes app using LoadBalancer
🔁 CI/CD Pipeline Flow
Code pushed to GitHub
CodePipeline triggers automatically
CodeBuild builds Docker image
Image pushed to ECR
EKS deploys updated application
📸 Screenshots

(Add screenshots here)

ECR Repository
CodePipeline Success
EKS Nodes
Application Running (LoadBalancer URL)
🌐 Application Access

http://

⚠️ Challenges Faced
IAM permission issues
ECR login failures
Kubernetes pod scheduling issues
Port mismatch (3000 vs 80)
LoadBalancer configuration issues
✅ Conclusion

Successfully implemented an automated CI/CD pipeline to deploy a containerized application on AWS EKS.
