# Node.js CI/CD Pipeline with GitHub Actions 🚀

This project demonstrates a basic CI/CD pipeline for a Node.js application using GitHub Actions. It runs tests, builds a Docker image, and pushes it to Docker Hub.

## 🔧 Tech Stack

- Node.js
- Express.js
- Docker 🐳
- GitHub Actions ⚙️

## 🚀 Pipeline Flow

1. Checkout code
2. Install dependencies
3. Run tests
4. Build Docker image
5. Push image to DockerHub

## 🛠️ Setup

- Create GitHub repository
- Add secrets:
  - `DOCKER_USERNAME`
  - `DOCKER_PASSWORD`

## 📦 Run Locally

```bash
npm install
node index.js