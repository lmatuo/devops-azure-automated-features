# Azure DevOps Pipeline for Agent and Storage Management
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

This Azure DevOps pipeline automates system monitoring and cleanup tasks on the build agent. It verifies the agent environment, checks disk storage, lists active processes, removes unnecessary files, and compares storage before and after cleanup.

## Features
- Detects and displays agent information.
- Monitors initial disk storage usage and publishes artifacts.
- Lists active processes on the agent.
- Cleans unnecessary packages and temporary files.
- Compares storage before and after cleanup.
- Provides structured logs for analysis.

## Requirements
- Azure DevOps account and project.
- Self-hosted or Microsoft-hosted agent with sudo privileges.
- Basic Linux utilities (`df`, `ps`, `awk`, `sed`, `grep`).
- Permissions to publish artifacts.

## How to Use

1. Clone the repository containing this pipeline.
2. Configure the `vars.yml` and `azure-pipelines-agent-pool.yml` files to set necessary parameters.
3. Add the pipeline YAML file (`azure-pipelines-agent-pool.yml`) to your Azure DevOps project.
4. Run the pipeline and monitor execution through Azure DevOps.
5. Review the final storage comparison results for validation.

## Schedule 🕓

The pipeline is set to run automatically every **Friday at 18:00 UTC** using a cron schedule.

_This cron schedule ensures that the pipeline will trigger every Friday **without needing manual intervention**._

## Warning

> ⚠️ **Warning**: Values marked with ⚠️ should be replaced according to your project's specific requirements.

## How to Use
1. Clone the repository containing this pipeline.
2. Configure the `vars.yml` file to set necessary parameters.
3. Add the pipeline YAML file (`azure-pipelines.yml`) to your Azure DevOps project.
4. Run the pipeline and monitor execution through Azure DevOps.
5. Review the final storage comparison results for validation.