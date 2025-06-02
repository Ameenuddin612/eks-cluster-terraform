# EKS Cluster with Terraform
This project provisions a complete AWS infrastructure using Terraform to deploy an Amazon EKS (Elastic Kubernetes Service) cluster. The goal was to automate the setup of a production-ready Kubernetes environment from scratch using Infrastructure as Code.

### Work Done:
- Designed and provisioned a custom VPC with public and private subnets
- Configured Internet Gateway, NAT Gateway, and route tables for network routing
- Created security groups and IAM roles for EKS and node group access
- Provisioned an EKS cluster using Terraform without relying on pre-built modules
- Wrote modular and reusable Terraform code to manage infrastructure efficiently
- Validated the setup with successful Terraform `apply` runs

This project demonstrates end-to-end automation of Kubernetes cluster infrastructure on AWS using Terraform, aligned with real-world DevOps practices.
