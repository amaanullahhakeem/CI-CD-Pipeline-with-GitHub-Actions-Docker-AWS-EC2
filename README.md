# Project Title: CI-CD-Pipeline-with-GitHub-Actions-Docker-AWS-EC2


# Project Overview:

This project demonstrates a CI/CD pipeline that automatically builds and deploys a containerized application whenever code is pushed to the repository.

The pipeline uses GitHub Actions to automate the process of building a Docker image, pushing it to Docker Hub, and deploying the application to an EC2 instance. This ensures faster and consistent application delivery with minimal manual intervention.

The solution follows modern DevOps practices by integrating version control, containerization, and automated deployment in a single workflow.

#  Project Description:


The goal of this project is to implement an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline.

Whenever a developer pushes code to the GitHub repository:

The CI/CD workflow is triggered.

The application is built inside a Docker container.

The Docker image is pushed to Docker Hub.

The application can then be deployed to an EC2 server.

This automation reduces deployment errors and speeds up the software delivery process.

#  Architecture:

Developer
   ↓
GitHub Repository
   ↓
GitHub Actions Workflow
   ↓
Build Docker Image
   ↓
Push Image to Docker Hub
   ↓
Deploy on AWS EC2
   ↓
Application Accessible via Browser

# Tools used:

GitHub

GitHub Actions

Docker

Amazon EC2

Amazon Web Services

# Technologies Used:

GitHub (Source Code Management)

GitHub Actions (CI/CD pipeline)

Docker (Containerization)

AWS EC2 (Application hosting)

Linux (Server environment)
