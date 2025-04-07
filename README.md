# Node.js Demo App 🚀

A simple Node.js application deployed using a CI/CD pipeline with GitHub Actions and Docker.

## 🧰 Tech Stack
- Node.js
- Express.js
- Docker
- GitHub Actions

## 🛠️ Features
- Basic Express server
- Dockerized app
- CI/CD workflow: Build → Push Docker image on each push to `main` branch

## 🐳 DockerHub
Image automatically pushed to DockerHub:  
👉 https://hub.docker.com/repository/docker/abrarkivande/nodejs-demo-app

## 📦 Run Locally
```bash
git clone https://github.com/AbrarKivande/nodejs-demo-app.git
cd nodejs-demo-app
docker build -t nodejs-demo-app .
docker run -p 3000:3000 nodejs-demo-app

🔁 CI/CD Workflow
Defined in .github/workflows/main.yml:

Install dependencies

Build Docker image

Push to DockerHub on every push to main

Made with ❤️ for learning DevOps automation.
