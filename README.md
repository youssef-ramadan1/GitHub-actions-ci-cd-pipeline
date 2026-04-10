 # Hybrid CI/CD Pipeline: GitHub Actions & Docker

## 📝 Overview
This project demonstrates a fully automated CI/CD pipeline designed to containerize and deploy a web application. It implements a *Hybrid approach* by leveraging a *Self-hosted Runner* on a local Linux environment for secure, on-premise deployment.

---

## 🛠 Tech Stack
* *CI/CD:* GitHub Actions
* *Containerization:* Docker & Docker Hub
* *Environment:* Linux (Self-hosted Runner)
* *Web Server:* Nginx / HTML5

---

## 🏗 Architecture
1. *Code Push:* Developer pushes code to the main branch.
2. *CI Stage:* GitHub Actions triggers a workflow to build a Docker image.
3. *Image Push:* The image is tagged and pushed to *Docker Hub*.
4. *CD Stage:* The *Self-hosted Runner* pulls the latest image and deploys it locally.

---

## 🔒 Security & Automation
* *GitHub Secrets:* Managed Docker Hub credentials and environment variables securely.
* *Automated Workflow:* Integrated triggers to ensure consistent and reliable delivery.
* *Deployment Control:* Configured a secure local environment for the runner to manage deployments directly.
*
