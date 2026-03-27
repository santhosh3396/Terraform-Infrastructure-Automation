# Terraform AWS Infrastructure Automation

This project uses Terraform to create an AWS EC2 instance and install Apache web server automatically.

## Features
- Infrastructure as Code using Terraform
- AWS EC2 provisioning
- Apache installation using user_data script
- CI/CD using GitHub Actions

## Project Structure
.
├── environments/dev/main.tf
├── install_apache.sh
├── main.tf
└── .github/workflows/terraform.yml

## How to Run

1. Go to dev environment:
cd environments/dev

2. Initialize Terraform:
terraform init

3. Apply configuration:
terraform apply

## Output
- EC2 instance will be created
- Apache web server will be installed
- You can access website using EC2 Public IP

## Tools Used
- Terraform
- AWS
- GitHub Actions

## Author
Santhosh Gurujupalli
