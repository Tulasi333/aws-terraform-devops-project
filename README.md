# AWS Infrastructure Automation using Terraform

## Project Overview
This project demonstrates how to provision AWS infrastructure using Terraform (Infrastructure as Code).

## Tools Used
- AWS
- Terraform
- Git
- GitHub

## Infrastructure Created
The Terraform configuration creates the following resources:

- VPC
- Public Subnet
- Internet Gateway
- Security Group
- EC2 Instance

## Project Structure

aws-terraform-devops-project
│
├── provider.tf
├── main.tf
├── variables.tf
├── outputs.tf

## How to Run the Project
1. Configure AWS CLI
2. Initialize Terraform
terraform init

3. Check infrastructure plan
terraform plan

4. Deploy infrastructure
terraform apply

## Outcome
Successfully automated AWS infrastructure provisioning using Terraform.
