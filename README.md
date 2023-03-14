# Automated ECR-ECS deployments

Create the AWS infrastructure (ECS,ALB,VPC,SG) to deploy a container.

# Core components

# AWS
The AWS infrastructure is setup using terraform in the ./ecs.tf.

The following components are deployed :

- Application Load Balancer
- ECS Cluster / ECS Service 
- VPC configuration
- SG configuration
