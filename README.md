# 🛠️ Notes App CI/CD Pipeline using Jenkins + Docker

This project demonstrates a complete CI/CD pipeline built using **Jenkins**, **Docker**, and **Docker Compose** to build, push, and deploy a simple Note-Taking app.

Every time code is pushed to the `main` branch, the pipeline:
1. Clones the repository
2. Builds a Docker image
3. Pushes it to Docker Hub
4. Deploys it using `docker-compose up -d`

---

## 🚀 Tech Stack

- **Jenkins** – CI/CD automation
- **Docker** – Containerization
- **Docker Hub** – Container registry
- **Docker Compose** – Multi-container deployment
- **GitHub** – Source code version control
