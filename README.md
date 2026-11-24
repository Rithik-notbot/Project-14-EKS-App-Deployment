# Project 14 - App Deployment using Amazon EKS

## Objective
Deploy a containerized application using Amazon Elastic Kubernetes Service (EKS).

## Planned Implementation
1. Configure an approved AWS VPC and subnets.
2. Provision an EKS cluster using Terraform.
3. Create an EKS managed node group.
4. Configure kubectl access.
5. Deploy a sample application.
6. Expose the application using a Kubernetes Service.
7. Verify application availability.

## Tools and Technologies
- AWS EKS
- AWS EC2
- Terraform
- Kubernetes
- kubectl
- Docker
- Git
- GitHub

## Security
- Use company-approved AWS infrastructure.
- Follow least-privilege IAM permissions.
- Do not commit credentials or secrets.
- Restrict cluster access to approved administrators.
- Obtain approval before creating chargeable AWS resources.

## Current Status
- Terraform configuration created.
- EKS cluster and managed node group defined.
- Terraform formatting and validation completed.
- Terraform plan completed: 8 resources to add.
- Kubernetes namespace, deployment, and service manifests created.
- kubectl installed and verified.
- AWS deployment pending company approval.
- Kubernetes application deployment and testing pending.