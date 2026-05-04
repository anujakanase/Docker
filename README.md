* This repository contains hands-on Docker projects demonstrating real-world DevOps practices including:

- Containerization of applications

- Multi-stage Docker builds

- Lightweight production-ready images

- Running and managing containers

# 🛠️ Tech Stack

- 🐳 Docker

- 🐍 Python

- ☕ Java

- 🌐 Nginx

- 🐧 Linux

🧠 Key Learnings:

- Writing efficient Dockerfiles

- Multi-stage builds for optimization

- Container lifecycle management

- Port mapping and networking

- Reducing image size using slim images

📂 Projects Included

🔹 1. Nginx Deployment
- Containerized Nginx web server
- Custom static web page
- Port mapping and container exposure
  
🔹 2. Flask Application (Python)
- Simple Flask web application
- Dockerized Python environment
- Application served via container

🔹 3. Java Application
- Basic Java application containerization
- Demonstrates Java runtime inside Docker
- Lightweight build and execution
  
▶️ Running the Applications

🔹 Run Nginx Container

cd nginx-docker

docker build -t nginx-app .

docker run -d -p 80:80 nginx-app

🌐 Access:
http://<pubilc_ip>:80

🔹 Run Flask Application

cd flask-app

docker build -t flask-app .

docker run -d -p 5000:5000 flask-app

🌐 Access:
http://<public_ip>:5000

🔹 Run Java Application
cd java-app
docker build -t java-app .
docker run java-app


