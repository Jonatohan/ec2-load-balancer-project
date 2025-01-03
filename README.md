# EC2 Load Balancer Portfolio Project

This repository contains Terraform configurations for setting up an EC2 instance with a load balancer. The purpose of this project is to demonstrate my skills in Infrastructure as Code (IaC) using Terraform and AWS. This project is part of my portfolio to showcase my abilities to potential employers.

## Project Structure

- *main.tf*: Contains the primary Terraform configuration for provisioning the EC2 instance and load balancer.
- **variables.tf**: Defines the variables used in the configuration 
- **outputs.tf**: Specifies the outputs of the Terraform configuration 
- **.gitignore**: Specifies files and directories to be ignored by Git.

## Project Details

- *EC2 Instance*: 
  - AMI: Amazon windows 10
  - Instance Type: t3.micro
  - Security Group: `EC2-ELB-portfolio`

- **Load Balancer**: 
  - Type: Classic Load Balancer
  - Listeners: HTTP on port 80
  - Health Check: HTTP on port 80

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ec2-load-balancer-project.git
