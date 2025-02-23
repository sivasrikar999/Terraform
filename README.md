# Terraform

Terraform AWS Infrastructure Setup

This Terraform project provisions an EC2 instance and an S3 bucket in the us-east-1 region. It defines:

An EC2 instance using an AMI ID and instance type from variables.
An S3 bucket configured with a secondary AWS provider alias (secondary).
The default AWS provider manages the EC2 instance, while the aliased provider is used for the S3 bucket.
Run terraform init, terraform apply -auto-approve to deploy. 🚀

This setup provides a scalable, reusable infrastructure for AWS deployments.
