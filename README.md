**_The documentation for this project can be found here: [Automate Infrastructure With IaC using Terraform 2](https://github.com/mimi-netizen/Steghub-DevOps_CloudComputing/tree/main/Project%2017%20Automate%20Infrastructure%20With%20IAC%20using%20Terraform%20Part%202)_**

# Terraform-project17

This repository contains Terraform code for a cloud infrastructure project. The project sets up the following resources:

1. AWS VPC
2. Public and private subnets
3. Internet Gateway
4. NAT Gateway
5. Route tables
6. Security groups
7. Elastic Load Balancer (ELB)
8. Auto Scaling Groups (ASGs) for bastion, Nginx, and WordPress/Tooling instances
9. Elastic File System (EFS)
10. Amazon RDS database
11. Terraform Vars

## Prerequisites

Before you can use the Terraform code in this repository, you'll need to have the following installed and configured on your system:

- Terraform
- AWS CLI
- AWS account with necessary permissions

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mimi-netizen/Terraform-project17.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Terraform-project17/PBL
   ```

3. Initialize the Terraform working directory:

   ```bash
   terraform init
   ```

4. Review the Terraform configuration files and make any necessary changes to variables or resource settings.

5. Create an execution plan:

   ```bash
   terraform plan -out tfplan
   ```

6. Apply the plan to create the infrastructure:

   ```bash
   terraform apply tfplan
   ```

7. When you're done, you can destroy the infrastructure using the following command:

   ```bash
   terraform destroy -auto-approve
   ```

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.
