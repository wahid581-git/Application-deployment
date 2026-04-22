GitHub 
→ CodePipeline 
→ CodeBuild 
→ ECR
→ EKS
→ LoadBalancer 
→ User

FLOW:
1.Code pushed to GitHub
2.Pipeline triggers
3.CodeBuild builds Docker image
4.Image pushed to ECR
5.EKS pulls image and deploys
6.LoadBalancer exposes app
