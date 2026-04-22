GitHub → CodePipeline → CodeBuild → ECR → EKS → LoadBalancer → User

FLOW:
Code pushed to GitHub
Pipeline triggers
CodeBuild builds Docker image
Image pushed to ECR
EKS pulls image and deploys
LoadBalancer exposes app
