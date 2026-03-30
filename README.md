
# DevOps Setup Project 🚀

## 📌 Overview
This project covers complete DevOps beginner setup:

- WSL (Ubuntu) installation  
- Git & GitHub setup  
- Docker installation and containers  
- AWS (EC2, S3, IAM)  

---

## 🖥️ Step 1: WSL Setup
- Installed Windows Subsystem for Linux (WSL)  
- Installed Ubuntu  
- Created user and configured terminal  

---

## 🔧 Step 2: Git Setup
- Installed Git  
- Configured username and email  
- Connected GitHub using SSH key  

---

## 🐳 Step 3: Docker Setup
- Installed Docker  
- Ran hello-world container  

---

## ☁️ Step 4: AWS Setup
- Created EC2 instance  
- Created S3 bucket  
- Configured IAM  

---

## 🚀 Conclusion
This project demonstrates hands-on DevOps setup.
## 📌 Overview
This project covers complete DevOps beginner setup:
- WSL (Ubuntu) installation
- Git & GitHub setup
- Docker installation and containers
- AWS (EC2, S3, IAM)

---

## 🖥️ Step 1: WSL Setup
- Installed Windows Subsystem for Linux (WSL)
- Installed Ubuntu
- Created user and configured terminal

---

## 🔧 Step 2: Git Setup
- Installed Git
- Configured username and email
- Connected GitHub using SSH key

---

## 🔐 Step 3: GitHub SSH Setup
Commands used:
ssh-keygen -t ed25519 -C "your-email@gmail.com"
cat ~/.ssh/id_ed25519.pub

---

## 🐳 Step 4: Docker Setup

### Install Docker
sudo apt install docker.io -y

### Run container
docker run hello-world

---

## 🌐 Step 5: Apache using Docker
docker run -d -p 8080:80 httpd

Access:
http://localhost:8080

---

## 🌐 Step 6: Nginx using Docker
docker run -d -p 8090:80 nginx

Access:
http://localhost:8090

---

## ☁️ Step 7: AWS Setup

### EC2
- Created EC2 instance
- Connected using SSH

### S3
- Created S3 bucket
- Uploaded files

### IAM
- Created users and roles
- Assigned permissions

---

## 📂 Project Structure
devops-setup-project/
 └── README.md

---

## 🚀 Conclusion
This project demonstrates hands-on DevOps setup including Linux, Git, Docker, and AWS.
