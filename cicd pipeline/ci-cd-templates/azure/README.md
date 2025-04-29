# Azure DevOps Pipeline for Node.js Applications

This directory contains a reusable Azure DevOps pipeline template for Node.js applications.

## Usage

1. Copy the `azure-pipelines.yml` file to your project's root directory.
2. Create a new pipeline in Azure DevOps and point it to your repository.
3. Customize the parameters in the pipeline file as needed.

## Features

- Build and test Node.js applications
- Configurable Node.js versions
- Caching of npm dependencies for faster builds
- Linting and code quality checks
- Unit and integration testing
- Docker image building and pushing
- Deployment to different environments (dev, staging, production)
- Environment-specific variables and configurations

## Requirements

- Azure DevOps account
- Repository with a Node.js application
- Package.json with appropriate scripts for linting, testing, and building
- Azure subscription for deployments
- Service connections for Azure and Docker registry