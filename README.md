# AWS CI/CD Pipeline

• Stages of the whole pipeline is built using CodePipeline.

• Artifact built by CodeBuild is stored in S3.

• Commits made to CodeCommit create a new docker image which is pushed to ECR.

• CodeDeploy is used to automate the deployment of application to ECS Fargate.

• Used Application Load Balancer to expose the ports and configure security groups.