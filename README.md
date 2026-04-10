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
## 📸 Project Screenshots:

![1](https://github.com/user-attachments/assets/0dcdfadb-ca24-4ffc-b35c-813c8b77d0fa)

<img width="1895" height="1045" alt="1" src="https://github.com/user-attachments/assets/445035c8-6589-4bc3-9fdc-4551500b032e" />

![eae800b8-4f22-45c4-a9a4-a58527ef19e2](https://github.com/user-attachments/assets/5c84f7cd-8fbf-4463-8c66-9ca16c5c0fad)

![1 (2)](https://github.com/user-attachments/assets/86fbad83-8b2d-4a07-ba25-0da78b551da0)





