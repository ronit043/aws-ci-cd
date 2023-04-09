# AWS CI/CD Pipeline

• Stages of the whole pipeline is built using CodePipeline.

• Artifact built by CodeBuild is stored in S3.

• Commits made to CodeCommit create a new docker image which is pushed to ECR.

• CodeDeploy is used to automate the deployment of application to ECS Fargate.

• Used Application Load Balancer to expose the ports and configure security groups.

## Screenshot
![AWS-CI-CD-website](https://user-images.githubusercontent.com/72982923/230766150-c677dcb0-c2b7-4b54-8d5e-f1d11cb49ac3.png)
