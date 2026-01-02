# Osayl Resume – DevOps Portfolio

Personal resume & portfolio website built with **React** and deployed as a
**production-ready application** using **Docker**, **GitHub Actions CI/CD**,
and **Oracle Cloud VM**.

Live site: http://151.145.93.131/

---

## 🛠 Tech Stack

### Frontend
- React (Create React App)
- JavaScript (ES6)
- HTML5 / CSS3

### DevOps & Infrastructure
- Docker (multi-stage, multi-architecture)
- GitHub Actions (CI/CD)
- Docker Hub
- Oracle Cloud VM (Linux, ARM)
- Linux & SSH
- **Cron daemon (scheduled automation)**

---

## 🚀 CI/CD Pipeline

The project uses a full CI/CD pipeline:

1. Code pushed to GitHub
2. GitHub Actions workflow triggered
3. Dependencies installed and React app built
4. Docker image built (multi-stage)
5. Multi-architecture image (amd64 / arm64) pushed to Docker Hub
6. Deployment to Oracle Cloud VM via SSH
7. Application served using Nginx

