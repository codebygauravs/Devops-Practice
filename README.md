# DevOps  Project 🚀

[![Docker Build CI](https://github.com/codebygauravs/Devops-Practice/actions/workflows/docker-build.yml/badge.svg)](https://github.com/codebygauravs/Devops-Practice/actions/workflows/docker-build.yml)

A lightweight Node.js Express microservice containerized with Docker and verified via automated GitHub Actions CI.

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js
- **Containerization:** Docker (Alpine Linux)
- **CI/CD:** GitHub Actions

## 🐳 Run Locally with Docker

### 1. Build the Docker Image
```bash
docker build -t devops-beginner-app .
```

### 2. Run the Container
```bash
docker run -d -p 3000:3000 --name devops-app devops-beginner-app
```

### 3. Verify
Open http://localhost:3000 in your browser.

## 🔄 CI Pipeline
On every push or pull request to main, GitHub Actions automatically builds and validates the Docker image.
