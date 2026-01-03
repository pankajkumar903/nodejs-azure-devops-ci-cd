# Node.js CI/CD with npm and Docker 

This project demonstrates an end-to-end CI/CD pipeline for a Node.js application using npm and Azure DevOps.

## Features
- Node.js application with npm scripts
- Linting, unit testing, and build stages
- Build artifact generation and publishing
- Docker image creation using Dockerfile
- CI pipeline configured with Azure DevOps YAML

## CI/CD Flow
1. Code push to main branch triggers pipeline
2. Install Node.js and npm dependencies
3. Run lint and unit tests using npm
4. Generate build artifact (dist folder)
5. Publish build artifact
6. Build Docker image and tag with build ID
7. (Optional) Push Docker image to container registry

## Tech Stack
- Node.js
- npm
- Jest
- Docker
- Azure DevOps Pipelines

## Use Case
This repository is suitable for learning or demonstrating modern CI/CD practices for Node.js applications, including artifact management and containerization.

