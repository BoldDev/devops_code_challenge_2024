# DevOps Tech Challenge: CI/CD Pipeline Implementation and Infrastructure Automation
## Objective
The goal of this exercise is to demonstrate your ability to implement a CI/CD pipeline and automate infrastructure provisioning using industry-standard tools. You will create a simple web application, containerize it, deploy it to a cloud provider, and set up continuous integration and continuous deployment.

## Prerequisites
- Basic knowledge of Docker, Jenkins, Terraform, and a cloud provider (AWS, GCP, or Azure).
- Exercise Steps
- Web Application Development

Create a simple web application using any language or framework of your choice (e.g., Node.js, Python Flask, Java Spring Boot).
Ensure the application has at least one endpoint (e.g., /hello that returns "Hello, World!").

## Containerization

Write a Dockerfile to containerize your application.
Ensure the Dockerfile includes all necessary instructions to build and run your application.

## Version Control

Initialize a Git repository and push your code to a public or private repository on GitHub or GitLab.

## CI/CD Pipeline Setup

- Set up a Jenkins server or use a CI/CD service provided by GitHub/GitLab.
- Create a Jenkinsfile (or the respective configuration file for GitHub/GitLab CI) to:
- Build the Docker image.
- Push the Docker image to a container registry (e.g., Docker Hub, AWS ECR, GCP Container Registry) DON'T NEED TO ACTUALLY PUSH THE IMAGE.

## Infrastructure as Code (IaC)

- Use Terraform to write a configuration that provisions the necessary infrastructure on your chosen cloud provider.
- The infrastructure should include:
-- A managed Kubernetes cluster (e.g., EKS on AWS, GKE on GCP, AKS on Azure) or a simple VM if preferred.
-- Any necessary networking components (VPC, subnets, security groups, etc.).

## Deployment

- Write Kubernetes manifests or Docker Compose files to deploy your application on the provisioned infrastructure.
- Ensure your application is accessible via a public endpoint (e.g., using an ingress controller in Kubernetes).

## Automated Deployment

- Extend your CI/CD pipeline to automatically deploy the application to the cloud provider whenever there is a new push to the main branch.

## Documentation

- Provide a README file in your repository with:
- Instructions on how to build and run the application locally.
- Steps to set up the CI/CD pipeline.
- How to provision the infrastructure using Terraform.
- How to deploy the application manually if needed.
- Any additional details you find relevant.

## Deliverables
- The web application source code.
- Dockerfile.
- Jenkinsfile or equivalent CI/CD configuration.
- Terraform configuration files.
- Kubernetes manifests or Docker Compose files.
- README file with comprehensive instructions.

# Evaluation Criteria
- Correctness: The application runs and functions as expected.
- Completeness: All steps are followed, and deliverables are provided as specified.
- Code Quality: Clean, readable, and well-documented code.
- Automation: Effective use of CI/CD and IaC to automate the build, test, and deployment process.
- Documentation: Clear and comprehensive instructions.
## Bonus Points
- Implementing a staging environment.
- Using advanced CI/CD features like environment-specific configurations or rollback mechanisms.
- Monitoring and logging setup (e.g., using Prometheus and Grafana).

Good luck, and happy coding!
