# AWS CodePipeline for Node.js Applications

This directory contains a CloudFormation template for setting up an AWS CodePipeline for Node.js applications.

## Usage

1. Upload the `codepipeline.yml` file to an S3 bucket.
2. Create a new CloudFormation stack using the template.
3. Provide the required parameters during stack creation.

## Features

- Source code integration with GitHub or AWS CodeCommit
- Build stage using AWS CodeBuild
- Test stage for running unit and integration tests
- Deployment stages for different environments (dev, staging, production)
- Approval gates between environments
- Notifications for pipeline events

## Requirements

- AWS account with appropriate permissions
- Source code repository (GitHub or AWS CodeCommit)
- S3 bucket for artifacts
- IAM roles and policies for CodePipeline and CodeBuild

## Parameters

The template requires the following parameters:

- `RepositoryName`: The name of your source code repository
- `BranchName`: The branch to use for the pipeline
- `NodejsVersion`: The Node.js version to use
- `BuildCommand`: The command to build your application
- `TestCommand`: The command to test your application
- `ArtifactBucket`: The S3 bucket to store pipeline artifacts