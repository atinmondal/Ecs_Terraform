# Automated ECR-ECS deployments

Create the AWS infrastructure (ECS, ECR, ALB,VPC,SG) to deploy a container.

# Core components

# AWS
The AWS infrastructure is setup using terraform in the ./terraform.

The following components are deployed (./ecs.tf):

Application Load Balancer
ECS Cluster / ECS Service 
VPC configuration
SG configuration
