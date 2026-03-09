# starbucks-clone-cicd-jenkins-docker
devops jenkins docker cicd cloud containerization

☕ Starbucks Clone – CI/CD Deployment with Jenkins & Docker

This repository demonstrates the deployment automation of a Starbucks Clone application using a CI/CD pipeline built with Jenkins and Docker.

The goal of this implementation is to automate the build, containerization, and deployment process, following real-world DevOps practices.

🚀 Project Overview

In this setup, a CI/CD pipeline is configured using Jenkins to automatically build the application, create a Docker image, and push it to a container registry.

The application is deployed on a cloud virtual machine, enabling automated and consistent delivery.

🏗 Architecture Workflow
Developer → GitHub Repository → Jenkins Pipeline → Build Application
        → Docker Image Creation → Push to DockerHub → Deploy Container
⚙️ Configuration Workflow

Provisioned a VM instance on Google Cloud Compute Engine

Installed Docker Engine

Installed and configured Jenkins

Installed required Jenkins plugins

Connected GitHub repository to Jenkins

Created a Jenkins Declarative Pipeline

Built the application

Created Docker image

Tagged and pushed the image to DockerHub

Deployed the containerized application

🔁 Jenkins Pipeline Stages
Stage	Description
Checkout SCM	Pull source code from Git repository
Tool Initialization	Load required Jenkins tools
Clean Workspace	Remove previous build artifacts
Git Checkout	Clone application repository
Install Dependencies	Install application dependencies
Build Docker Image	Create container image
Tag & Push Docker Image	Push image to DockerHub
🛠 Tech Stack

CI/CD Tool: Jenkins

Containerization: Docker

Cloud Platform: Google Cloud Platform (Compute Engine)

Operating System: Ubuntu Linux

Version Control: Git & GitHub

Container Registry: DockerHub

📊 Key DevOps Learnings

Building automated CI/CD pipelines

Implementing Docker containerization

Integrating GitHub with Jenkins

Managing Docker images and registries

Automating build and deployment workflows

Understanding real-world DevOps automation

Add Kubernetes deployment

Implement Infrastructure as Code using Terraform

Integrate Monitoring with Prometheus & Grafana

Implement GitHub Webhooks for automatic pipeline trigger

👩‍💻 Author

Nazneen Fatima

Linux & Cloud Engineer | DevOps Enthusiast

📧 nazneenfatima668@gmail.com

⭐ If you found this useful

Give this repository a star ⭐ and feel free to fork it.
