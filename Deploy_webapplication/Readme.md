# DevOps Project: CI/CD with Jenkins, Docker, and Terraform

## Overview
This project demonstrates a complete DevOps workflow:
1. **Infrastructure provisioning with Terraform** on AWS.
2. **CI/CD Pipeline with Jenkins**, Docker, and DockerHub.
3. **Application deployment on AWS EC2.**

## Prerequisites
- AWS account
- Terraform installed locally
- Jenkins installed on an EC2 instance
- DockerHub account

## Workflow
1. **Provision infrastructure**: Use Terraform to create an EC2 instance for Jenkins.
2. **CI/CD Pipeline**:
   - Clone the repository.
   - Build and push a Docker image to DockerHub.
   - Deploy the application on an AWS EC2 instance.

## How to Run
1. Configure AWS credentials locally.
2. Run `terraform init` and `terraform apply` in the `terraform/` directory.
3. Access the Jenkins server on `<public-ip>:8080` and set up the pipeline.
4. Trigger the Jenkins job to deploy the application.
