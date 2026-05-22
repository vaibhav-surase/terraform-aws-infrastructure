# Terraform AWS Infrastructure Project

##  Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform to provision AWS infrastructure. It automates the creation of cloud resources such as EC2 instances using best practices.

---

## Tech Stack
- Terraform
- AWS (EC2, IAM)
- AWS CLI
- Linux (Ubuntu)
- Git & GitHub

---

## Project Structure

terraform-project/

│── main.tf

│── variables.tf

│── outputs.tf

│── provider.tf

│── .gitignore

│── README.md

## ⚙️ Features
- Infrastructure as Code (IaC) using Terraform
- Automated EC2 instance provisioning
- Secure AWS provider configuration
- Reusable and modular code structure
- Clean Git repository (no sensitive files)

  ---

## 🔧 Prerequisites
Make sure you have:

- AWS Account
- AWS CLI configured
- Terraform installed
- Git installed

---

## 🔐 AWS Configuration
Configure AWS credentials:

```bash
aws configure

AWS Access Key : AKIAQESXC3WMUCATXDCW
AWS Secret : Key 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
Region :  ap-south-1
Output format: json

How to Run
1. Initialize Terraform
terraform init
2. Validate configuration
terraform validate
3. Plan infrastructure
terraform plan
4. Apply infrastructure
terraform apply

Type yes when prompted.

📤 Output

After deployment, Terraform will output:

EC2 Public IP
Instance ID
🧹 Cleanup

To destroy infrastructure:

terraform destroy
📌 Notes
.terraform/ folder is ignored using .gitignore
terraform.tfstate is not pushed to GitHub
This project follows best practices for DevOps and IaC
👨‍💻 Author

Vaibhav Surase
DevOps Engineer
