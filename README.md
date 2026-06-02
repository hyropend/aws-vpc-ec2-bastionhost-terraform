# AWS VPC & Bastion Host Infrastructure using Terraform

This project extends a basic AWS VPC deployment by introducing a Bastion Host architecture built with Terraform.

The goal of this lab is to understand how administrators can securely access resources inside a private network and to gain practical experience with Infrastructure as Code (IaC) using Terraform.

---

# Technologies

* AWS
* Terraform
* VPC
* EC2
* Bastion Host
* Elastic IP
* Security Groups
* Linux / SSH

---

# Project Features

* Custom AWS VPC
* Terraform-based infrastructure deployment
* Bastion Host EC2 instance
* Elastic IP assignment
* Security Group configuration
* SSH access architecture
* Infrastructure outputs and variables
* Reusable Terraform configuration

---

# Project Structure

The project is separated into multiple Terraform files to improve readability and maintainability.

Key components include:

* VPC configuration
* Security Groups
* Bastion Host instance
* Elastic IP allocation
* Terraform variables
* Outputs
* Local values
* Provisioners

---

# Why a Bastion Host?

A Bastion Host is a publicly accessible server that acts as a controlled entry point into a private network.

Historically, Bastion Hosts were widely used to:

* Access private EC2 instances
* Restrict SSH entry points
* Improve network security
* Centralize administrative access

The basic workflow is:

Internet → Bastion Host → Private Resources

---

# Modern Alternatives

While Bastion Hosts are still common in many environments, modern cloud architectures often prefer:

* AWS Systems Manager Session Manager
* Zero Trust access solutions
* Identity-based access controls
* VPN-based administrative access

These approaches reduce the need for publicly exposed SSH endpoints.

However, understanding Bastion Host architecture remains important because many existing environments still use this pattern and it helps build a strong foundation in AWS networking and security concepts.

---

# Learning Objectives

Through this project I practiced:

* AWS networking fundamentals
* Terraform Infrastructure as Code workflows
* Security Group design
* EC2 deployment automation
* Bastion Host architecture
* AWS resource management

---

# Future Improvements

Possible future enhancements include:

* Private Subnets
* NAT Gateway
* EKS Integration
* Session Manager Access
* Terraform Modules
* Multi-Environment Deployments
* Remote Terraform State
* CI/CD Integration

---

This repository was created for educational and learning purposes.
