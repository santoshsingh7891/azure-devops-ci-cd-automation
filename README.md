![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-CI%2FCD-blue)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![Nginx](https://img.shields.io/badge/Nginx-Web%20Server-green)
![License](https://img.shields.io/badge/License-MIT-green)

# Azure DevOps CI/CD Automation

Enterprise Azure DevOps CI/CD automation project using Docker, Nginx, YAML pipelines, monitoring, and deployment automation.

---

# 🚀 Project Overview

This project demonstrates an end-to-end CI/CD automation workflow using Azure DevOps Pipelines, Docker containerization, and Nginx deployment.

The solution automates:
- Source code integration
- Docker image build process
- Container deployment
- Deployment validation
- Monitoring and logging

This project highlights DevOps automation, Infrastructure as Code concepts, CI/CD best practices, and containerized application deployment workflows.

---

# 🏗️ Architecture Diagram

![Azure DevOps Architecture](architecture/azure-devops-architecture.png)

---

# ⚙️ Technologies Used

- Azure DevOps
- YAML Pipelines
- Docker
- Nginx
- GitHub
- Linux
- HTML/CSS
- CI/CD Automation

---

# ✨ Features

- Automated CI/CD pipeline
- Docker image build automation
- Containerized Nginx deployment
- GitHub integration
- YAML pipeline configuration
- Deployment validation
- Monitoring and logs collection
- DevOps workflow automation

---

# 📁 Project Structure

```text
azure-devops-ci-cd-automation/
│
├── architecture/
│   ├── azure-devops-architecture.png
│   └── README.md
│
├── screenshots/
│
├── logs/
│
├── Dockerfile
├── azure-pipelines.yml
├── nginx.conf
├── index.html
├── style.css
├── README.md
└── .gitignore
```

# 🔄 CI/CD Workflow

1. Developer pushes code to GitHub repository
2. Azure DevOps pipeline gets triggered
3. Docker image build process starts
4. Nginx container deployment is executed
5. Application deployment validation is performed
6. Monitoring and logs are generated

---

# 📸 Project Screenshots

## Architecture Diagram

![Architecture](architecture/azure-devops-architecture.png)

---

## Azure DevOps Pipeline

![Pipeline](screenshots/azure-pipeline.png)

---

## Docker Build Process

![Docker Build](screenshots/docker-build.png)

---

## Nginx Container Deployment

![Container](screenshots/nginx-container.png)

---

## Application Deployment Validation

![Deployment](screenshots/deployment-validation.png)

---

## Monitoring & Logs

![Logs](screenshots/monitoring-logs.png)

---

# 🚀 Deployment Steps

## Clone Repository

```bash
git clone https://github.com/santoshsingh7891/azure-devops-ci-cd-automation.git
```

## Build Docker Image

```bash
docker build -t nginx-webapp .
```

## Run Docker Container

```bash
docker run -d -p 80:80 nginx-webapp
```

---

# 🔐 Security Best Practices

- Secure CI/CD pipeline configuration
- Containerized deployment isolation
- Git-based version control
- Automated deployment validation
- Monitoring and operational logging

---

# 📈 Future Enhancements

- Kubernetes deployment integration
- Azure Kubernetes Service (AKS)
- Terraform automation
- SonarQube code quality analysis
- Prometheus & Grafana monitoring
- Multi-stage Docker builds
- GitHub Actions integration

---

# 🧹 Cleanup

```bash
docker stop <container_id>
docker rm <container_id>
docker rmi nginx-webapp
```

---

# 👨‍💻 Author

Santosh Singh  
Cloud & DevOps Engineer

---

# 🔗 Connect With Me

- LinkedIn: https://www.linkedin.com/in/santosh-singh-141a5775/
- GitHub: https://github.com/santoshsingh7891
