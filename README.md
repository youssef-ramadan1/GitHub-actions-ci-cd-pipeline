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

* <img width="1895" height="1045" alt="Screenshot 2026-04-10 213935" src="https://github.com/user-attachments/assets/739aebbf-6d90-4f1c-9382-4116ac9a6a56" />

## 📸 Project Screenshots
Here are the visual results of the successful CI/CD pipeline and deployment:
<img width="1919" height="1079" alt="Screenshot 2026-04-10 214057" src="https://github.com/user-attachments/assets/52b1f5f8-b73a-4472-a8f4-3d9385df019f" />
![fd6edb97-e546-4171-bf73-36908110bfb1](https://github.com/user-attachments/assets/06ef3406-f1b9-4665-a245-c0f8f42f12d7)
![154c76d3-d1db-4080-83b6-42d111ac0235](https://github.com/user-attachments/assets/ef2e0c23-c240-440d-afaa-59fa33514d67)
![Uploading Screenshot 2026-04-10 213935.png…]()
![eae800b8-4f22-45c4-a9a4-a58527ef19e2](https://github.com/user-attachments/assets/e9735a40-5d2a-4d22-aa31-9f32fcbd2fde)
