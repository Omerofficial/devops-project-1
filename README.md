# 🚀 CI/CD Pipeline with GitHub Actions & Docker

This project demonstrates a complete DevOps pipeline using GitHub Actions to automate the building, testing, and deployment of a simple Flask web application. The final Docker image is pushed to Docker Hub.

---

## 📦 Project Structure

devops-project-1/ ├── app.py ├── requirements.txt ├── Dockerfile └── .github/ └── workflows/ └── ci-cd.yml


---

## 💡 Features

- CI/CD pipeline using GitHub Actions
- Dockerized Flask application
- Image pushed to Docker Hub automatically on every commit to `main`
- Secrets managed securely via GitHub repository secrets

---

## 🛠 Tools & Technologies

- Python 3.9
- Flask
- Docker
- GitHub Actions
- Docker Hub

---

## 🐳 Docker Image

Image Repository: [omerahmed2001/devops-project-1](https://hub.docker.com/repository/docker/omerahmed2001/devops-project-1)

You can pull the image using:

```bash
docker pull omerahmed2001/devops-project-1:latest

🔧 How It Works
Code is pushed to the main branch

GitHub Actions triggers the workflow

Workflow installs dependencies and builds Docker image

Logs in to Docker Hub using secrets:

DOCKER_USERNAME

DOCKER_PASSWORD

Pushes the image to Docker Hub

📸 Screenshots

GitHub Actions ✅	Docker Hub Image 🐳
C:\Users\user\OneDrive\Pictures\Screenshots\Screenshot (141).png
C:\Users\user\OneDrive\Pictures\Screenshots\Screenshot (142).png
C:\Users\user\OneDrive\Pictures\Screenshots\Screenshot (143).png

👤 Author
Omer Ahmed
📧 omerahmed9224@gmail.com
📱 9010994527
🎓 DevOps Intern at Elevate Labs

✅ Status
✅ CI/CD pipeline successfully implemented
✅ Docker image builds and deploys automatically
✅ Ready for extension or production usage


