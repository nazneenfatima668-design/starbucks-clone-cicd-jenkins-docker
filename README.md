# starbucks-clone-cicd-jenkins-docker
devops jenkins docker cicd cloud containerization

☕ Starbucks Clone – CI/CD Deployment with Jenkins & Docker

This repository demonstrates the deployment automation of a Starbucks Clone application using a CI/CD pipeline built with Jenkins and Docker.

The goal of this implementation is to automate the build, containerization, and deployment process, following real-world DevOps practices.

🚀 Project Overview

In this setup, a CI/CD pipeline is configured using Jenkins to automatically build the application, create a Docker image, and push it to a container registry.

The application is deployed on a cloud virtual machine, enabling automated and consistent delivery.

🏗 Architecture Workflow
Developer
   │
   ▼
GitHub Repository
   │
   ▼
Jenkins CI/CD Pipeline
   │
   ▼
Build Application
   │
   ▼
Docker Image Creation
   │
   ▼
Push to DockerHub
   │
   ▼
Deploy Container
⚙️ Configuration Workflow

1️⃣ Provisioned VM on Google Cloud Compute Engine

2️⃣ Installed Docker Engine

3️⃣ Installed and configured Jenkins

4️⃣ Installed required Jenkins plugins

5️⃣ Integrated GitHub repository with Jenkins

6️⃣ Configured Jenkins declarative pipeline

7️⃣ Built application

8️⃣ Created Docker image

9️⃣ Tagged and pushed image to DockerHub

🔟 Deployed containerized application

🔁 Jenkins Pipeline Stages
| Stage                | Description                       |
| -------------------- | --------------------------------- |
| Checkout SCM         | Fetch source code from repository |
| Tool Initialization  | Load required Jenkins tools       |
| Clean Workspace      | Remove previous build artifacts   |
| Git Checkout         | Clone application source          |
| Install Dependencies | Install required packages         |
| Build Docker Image   | Create container image            |
| Tag & Push Image     | Push Docker image to DockerHub    |

🛠 Tech Stack

| Category           | Tools                       |
| ------------------ | --------------------------- |
| CI/CD              | Jenkins                     |
| Containerization   | Docker                      |
| Cloud              | Google Cloud Compute Engine |
| OS                 | Linux (Ubuntu)              |
| Version Control    | Git & GitHub                |
| Container Registry | DockerHub                   |


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
📸 Screenshots


👩‍💻 Author

Nazneen Fatima

Linux & Cloud Engineer | DevOps Enthusiast

📧 nazneenfatima668@gmail.com

LinkedIn:https://www.linkedin.com/in/nazneen-fatima-737223397

⭐ If you found this helpful, feel free to star the repository.
