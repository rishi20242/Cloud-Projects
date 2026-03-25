# 🚀 AWS Infrastructure Automation using Terraform

This project provisions AWS infrastructure using Terraform, following best practices for networking and security.

---

## 📌 Architecture

- Custom VPC
- Public and Private Subnets
- Internet Gateway
- Route Tables
- Security Groups
- EC2 Instances (Public & Private)

---

## 🛠️ Technologies Used

- Terraform
- AWS (EC2, VPC, Subnets, IGW, Security Groups)
- AWS CLI

---

## 📂 Project Structure
├── provider.tf
├── vpc.tf
├── subnets.tf
├── internet_gateway.tf
├── route_tables.tf
├── security_groups.tf
├── ec2.tf

To Run

terraform init
terraform validate
terraform plan
terraform apply
