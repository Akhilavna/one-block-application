# Automated AWS Infrastructure Deployment using Terraform and Ansible
Designed and implemented an automated infrastructure provisioning and application deployment pipeline on AWS using Terraform and Ansible.
This project eliminates manual cloud configuration by enabling scalable, fault tolerant web server deployment through Infrastructure as Code.

---
# Project Overview
This system automatically provisions a production ready AWS environment and deploys a web application on EC2 instances.
Terraform is used to create and manage infrastructure resources, while Ansible is used to configure the application environment and deploy source code on provisioned instances.

---
# Core Features
- Automated EC2 instance provisioning using Launch Templates
- Auto Scaling Group with dynamic instance management
- Elastic Load Balancer for traffic distribution
- Secure networking using Security Groups
- Remote Terraform backend with S3 versioning
- Automated Apache web server installation
- Git based application deployment using Ansible
- Infrastructure provisioning without AWS console interaction
- Scalable and highly available application hosting setup

---
# Tech Stack
- Terraform
- AWS EC2
- AWS Auto Scaling
- AWS Elastic Load Balancer
- AWS S3
- Ansible
- Apache Web Server
- Git
---
# Outcome
Implemented a repeatable Infrastructure as Code pipeline capable of provisioning scalable AWS compute resources and automatically deploying application code across multiple instances with load balanced traffic handling.
