# Azure DevOps Automated Features Repository
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

This repository contains various automated DevOps features for Azure, including pipelines for system monitoring, resource management, and infrastructure automation. Each feature is designed to optimize DevOps workflows and improve operational efficiency.

## Features
- **Agent and Storage Management Pipeline**: Monitors and cleans disk storage on the build agent.
- **Security & Compliance Checks**: Automates vulnerability scans and policy enforcement.
- **Log and Metrics Monitoring**: Collects and analyzes system performance and application logs.

## Requirements
- Azure DevOps account and project.
- Self-hosted or Microsoft-hosted agents, depending on the pipeline.
- Necessary permissions to deploy resources, run scripts, and manage artifacts.
- Dependencies such as Terraform, Azure CLI, and required Linux utilities (`df`, `ps`, `awk`, `sed`, `grep`).

## How to Use
1. Clone the repository to access available automation scripts and pipelines.
2. Configure the required environment variables and `vars.yml` files for different features.
3. Choose the pipeline that suits your needs and integrate it into your Azure DevOps project.
4. Execute the pipeline and monitor logs in Azure DevOps.
5. Review output artifacts and logs to ensure successful execution.

## Need Help?

If you need assistance or have any questions, feel free to contact me at [matuo.larissa@gmail.com](mailto:matuo.larissa@gmail.com).