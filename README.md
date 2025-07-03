# AWS CodePipeline Demo

A simple HTML application demonstrating AWS CodePipeline with Docker containerization.

## Files:
- `index.html` - Main application
- `Dockerfile` - Container configuration
- `buildspec.yml` - CodeBuild specification
- `appspec.yml` - CodeDeploy specification
- `scripts/` - Deployment scripts

## Setup:
1. Push to CodeCommit repository
2. Configure CodePipeline with Source, Build, and Deploy stages
3. Set environment variables in CodeBuild for ECR