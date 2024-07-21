<h1 align="center">🌟 DevOps End-to-End Basics Project 🌟</h1>

Welcome to the **DevOps End-to-End Basics Project**! This project is a comprehensive demonstration of an end-to-end DevOps pipeline, showcasing a basic portfolio web page built with Golang. The DevOps pipeline is implemented using Docker, Kubernetes, AWS EKS, Helm, GitHub Actions, and ArgoCD.

![DevOps Pipeline](https://img.shields.io/badge/DevOps-Pipeline-blue) ![Golang](https://img.shields.io/badge/Golang-Go-blue) ![Docker](https://img.shields.io/badge/Docker-Container-blue) ![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue) ![AWS EKS](https://img.shields.io/badge/AWS-EKS-orange) ![Helm](https://img.shields.io/badge/Helm-Package-blue) ![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-yellow) ![ArgoCD](https://img.shields.io/badge/ArgoCD-Continuous%20Delivery-orange)

## 📝 Introduction
This project serves as a learning tool for understanding the basics of DevOps by creating a simple portfolio web page with Golang. It covers the full spectrum of DevOps practices, from containerization to continuous integration and deployment, using state-of-the-art tools and platforms.

## ✨ Features
- 🚀 **Golang Portfolio Web Page**: A simple, yet elegant web page built with Golang.
- 🐳 **Docker**: Containerization of the web application for consistent and portable environments.
- ☸️ **Kubernetes**: Orchestration of containerized applications for scalable deployments.
- ☁️ **AWS EKS**: Managed Kubernetes service for seamless deployment in the cloud.
- 🧩 **Helm**: Package manager for Kubernetes, enabling easy deployment of applications.
- ⚙️ **GitHub Actions**: Automated CI/CD pipeline to streamline the development workflow.
- 📦 **ArgoCD**: Continuous delivery tool for Kubernetes, ensuring rapid and reliable deployments.

## 🔧 Technologies Used
- **Programming Language**: Golang
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Cloud Service**: AWS EKS
- **Package Management**: Helm
- **CI/CD**: GitHub Actions
- **Continuous Delivery**: ArgoCD

## 🏗️ Architecture
![Architecture Diagram](path/to/architecture-diagram.png)

The architecture involves the following components:
1. **Golang Application**: The core of the project, serving the portfolio web page.
2. **Docker**: Containers for the Golang application.
3. **Kubernetes**: Orchestrating the containers.
4. **AWS EKS**: Hosting the Kubernetes cluster in the cloud.
5. **Helm**: Managing Kubernetes resources.
6. **GitHub Actions**: Automating the CI/CD pipeline.
7. **ArgoCD**: Continuous delivery to the Kubernetes cluster.

## 🚀 Setup and Deployment
Follow these steps to set up and deploy the project:

### Prerequisites
- Docker installed on your local machine.
- Kubernetes cluster (local or AWS EKS).
- Helm installed.
- ArgoCD installed on the Kubernetes cluster.
- GitHub account with access to GitHub Actions.

### Step 1: Clone the Repository
```bash
git clone https://github.com/saiaryansahoo/DevOps-End-To-End-Basics-Project.git
cd DevOps-End-To-End-Basics-Project
```

### Step 2: Build the Docker Image
Navigate to the root directory of the project and build the Docker image using the following command:
```bash
docker build -t your-dockerhub-username/portfolio-webpage:latest .
```

### Step 3: Push the Docker Image to DockerHub
Login to DockerHub and push the image:
```bash
docker login
docker push your-dockerhub-username/portfolio-webpage:latest
```

### Step 4: Deploy to Kubernetes using Helm
Ensure your Kubernetes cluster is up and running. Then, deploy the application using Helm:
```bash
helm install portfolio-webpage ./helm-chart
```

### Step 5: Push the Docker Image to DockerHub
Set up the GitHub Actions workflow by creating a .github/workflows/main.yml file with the necessary configuration to automate the CI/CD pipeline.

### Step 6: Set Up ArgoCD
Install and configure ArgoCD on your Kubernetes cluster. Follow the official ArgoCD documentation for setup instructions.

## 📄Usage
Access the portfolio web page by navigating to the external IP of your Kubernetes cluster. The application should be up and running, showcasing the portfolio web page.

## 🤝Contributinh
Contributions are welcome! Please fork the repository and submit pull requests for any improvements or additions.

## 📜License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## 👤 About Me

Hi, I'm Sai Aryan Sahoo, the developer behind this project. I'm passionate about DevOps, cloud technologies, and continuous integration/continuous deployment (CI/CD) practices. This project is a demonstration of my skills and knowledge in building an end-to-end DevOps pipeline.

- Connect with me on [LinkedIn](https://www.linkedin.com/in/saiaryansahoo)
- Check out my other projects on [GitHub](https://github.com/saiaryansahoo)
- Reach me via email: [saiaryansahoo@example.com](mailto:saiaryansahoo@example.com)

