# GitLab CI/CD Pipeline for Node.js Applications

This directory contains a reusable GitLab CI/CD pipeline template for Node.js applications.

## Usage

1. Copy the `nodejs-pipeline.yml` file to your project's root directory as `.gitlab-ci.yml`.
2. Customize the parameters in the pipeline file as needed.
3. Commit and push the changes to your GitLab repository.

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

- GitLab repository with a Node.js application
- Package.json with appropriate scripts for linting, testing, and building
- GitLab Runner with Docker executor
- Docker registry credentials (if using Docker features)
- Deployment credentials (if using deployment features)