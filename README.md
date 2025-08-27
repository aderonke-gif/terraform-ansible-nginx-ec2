# terraform-ansible-nginx-ec2
This project provisions an AWS EC2 instance using Terraform and automatically configures it with Nginx using Ansible. It installs Nginx, starts the service, and deploys a custom welcome page — all done through automated scripts.
# Terraform + Ansible: Nginx on AWS EC2

##  Project Overview

This project provisions an AWS EC2 instance using **Terraform**, then configures it with **Nginx** using **Ansible**. It automates infrastructure setup and server configuration to deploy a simple welcome page on a public IP.

---

## Tech Stack

- **Terraform** – Infrastructure as Code
- **Ansible** – Configuration Management
- **AWS EC2** – Virtual server
- **Ubuntu** – Operating System
- 
- terraform-nginx-setup/
├── ansible/
│ ├── inventory # Ansible inventory with EC2 IP and SSH key path
│ └── playbook.yml # Nginx install and custom index.html deployment
├── *.tf # Terraform configuration files
├── key1.pem # Private key to SSH into EC2 (not to be committed)
└── README.md

---

## Project Structure

terraform-nginx-setup/
├── ansible/
│   ├── inventory
│   └── playbook.yml
├── main.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
├── README.md
└── key1.pem


