Two-Tier Flask Application (Flask + MySQL + Docker + AWS)


![download](https://github.com/user-attachments/assets/b7e6cb14-c405-447e-8a46-15bf2b1cda89)


A fully containerized Two-Tier Flask Application consisting of:

Flask Web Application

MySQL Database

Docker + Docker Compose orchestration

AWS EC2 Deployment

CI/CD support (Jenkinsfile & Makefile)

Kubernetes manifests (EKS ready)


Credit

This project is based on the original application developed by TrainWithShubham.
Original Repo: https://github.com/LondheShubham153/two-tier-flask-app

This repository focuses on deployment, containerization, debugging, and cloud setup done by Sachin D K


Project Structure


two-tier-flask-app/

│── eks-manifests/             # EKS Kubernetes YAML files

│── k8s/                       # Older K8s pod/service manifests

│── templates/                 # HTML templates for Flask

│── Dockerfile                 # Flask backend image

│── Dockerfile-multistage      # Optimized build for production

│── Jenkinsfile                # CI/CD pipeline for Jenkins

│── Makefile                   # Build automation

│── README.md                  # Documentation

│── app.py                     # Flask main application

│── docker-compose.yml         # Multi-container (Flask + MySQL)

│── dummy.txt                  # Placeholder / not used

│── message.sql                # DB initialization script

└── requirements.txt           # Python dependencies


