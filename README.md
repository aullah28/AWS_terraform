# AULLAH Terraform Getting Started Guide

I sued example Terraform configuration intended for use with the HCP account

## What will this do?

This is a Terraform configuration that will create an EC2 instance in my AWS account. 

When you set up a Workspace on HCP Terraform, you can link to this repository. HCP Terraform can then run `terraform plan` and `terraform apply` automatically when changes are pushed. For more information on how HCP Terraform interacts with Version Control Systems, see [our VCS documentation](https://www.terraform.io/docs/cloud/run/ui.html).

## What are the prerequisites?

The values for `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` should be saved as environment variables on your workspace.
