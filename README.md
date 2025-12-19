# 🚀 Node.js CI/CD Deployment using Jenkins & Ansible on AWS EC2

This project demonstrates an **end-to-end CI/CD pipeline** to automatically deploy a **Node.js application** on an **AWS EC2 instance** using **Jenkins**, **Ansible**, **PM2**, and **Nginx**.

---

## 📌 Project Overview

Whenever code is pushed to GitHub:
- Jenkins pulls the latest code from GitHub
- Ansible configures the EC2 instance
- Node.js app is deployed using PM2
- Nginx is reloaded to serve traffic

This setup reflects **real-world DevOps deployment practices**.

---

## 🏗 CI/CD Architecture Diagram

<p align="center">
  <img src="https://raw.githubusercontent.com/Rajiv1851/basic/main/images/cicd-architecture.png
" alt="CI/CD Architecture Diagram" width="800"/>
</p>

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,jenkins,ansible,nodejs,nginx,git" />
</p>

---

## 📂 Project Structure

```bash
.
├── app.js
├── package.json
├── Jenkinsfile
├── deploy.yml
├── hosts.ini
├── images
│   └── cicd-architecture.png
└── README.md
