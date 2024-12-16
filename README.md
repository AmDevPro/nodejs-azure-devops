# nodejs-azure-devops
To deploy a Node.js web application on Microsoft Azure using Terraform for Infrastructure as Code and an Azure DevOps CI/CD pipeline. This repository includes the Node.js app, Terraform scripts, and pipeline configuration.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Project Architecture](#project-architecture)
3. [Setup and Deployment](#setup-and-deployment)
   - [Step 1: Prepare Your Local Environment](#step-1-prepare-your-local-environment)
   - [Step 2: Build the Node.js Web Application](#step-2-build-the-nodejs-web-application)
   - [Step 3: Define Infrastructure with Terraform](#step-3-define-infrastructure-with-terraform)
   - [Step 4: Set Up CI/CD in Azure DevOps](#step-4-set-up-cicd-in-azure-devops)
4. [Testing and Monitoring](#testing-and-monitoring)


## Prerequisites
Before starting, ensure you have the following:
- A Microsoft Azure account ([sign up for free](https://azure.microsoft.com/free/)).
- An Azure DevOps account ([sign up here](https://dev.azure.com/)).
- Tools installed on your local machine:
  - [Terraform](https://developer.hashicorp.com/terraform/downloads)
  - [Node.js](https://nodejs.org/en/download/) (version 14 or later)
  - [Git](https://git-scm.com/)
  - [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Basic knowledge of Git, Node.js, and Azure.
