# eks-automode-demo
For Multi-tier web application

# Terraform Backend Setup
This directory contains the Terraform configuration to set up the S3 backend for storing Terraform state.
## Purpose
- Creates S3 bucket for Terraform state storage
- Creates DynamoDB table for state locking
- Enables encryption and versioning
- Blocks all public access
