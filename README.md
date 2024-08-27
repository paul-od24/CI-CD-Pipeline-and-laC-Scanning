# CI-CD-Pipeline-and-laC-Scanning
# CI/CD Pipeline with Terraform and IaC Scanning

This project demonstrates a CI/CD pipeline using GitHub Actions for Terraform deployments with integrated IaC security scanning.

## Features
- **CI/CD Pipeline**: Automatically validates, plans, and applies Terraform configurations.
- **IaC Security**: Includes a security scanning step using `tfsec`.

## Setup
1. Fork and clone the repository.
2. Add AWS credentials to GitHub Secrets.
3. Push changes to the `main` branch to trigger the pipeline.

## Tools Used
- **Terraform**: Infrastructure as Code.
- **GitHub Actions**: CI/CD automation.
- **tfsec**: Terraform security scanner.
