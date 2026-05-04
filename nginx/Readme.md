🚀 Nginx Deployment using Docker

This project demonstrates how to deploy a lightweight and scalable Nginx web server using Docker. It serves a static website and showcases containerization best practices.

📌 Project Overview

-Containerized Nginx using Docker

-Used Dockerfile for image creation

-Used Docker Compose for easy orchestration

-Demonstrates real-world DevOps fundamentals

🛠️ Tech Stack

Docker

Nginx

Docker Compose

📁 Project Structure

nginx/

│── Dockerfile
│── docker-compose.yml
│── index.html
│── README.md

⚙️ Setup & Installation

1️⃣ Clone the Repository
git clone https://github.com/anujakanase/docker.git

cd nginx

2️⃣ Build Docker Image

docker build -t nginx .

3️⃣ Run the Container

docker run -d -p 80:80 --name nginx-container nginx:latest

4️⃣ Access Application

Open in browser: http://<public_ip of instance>:80

🐳 Using Docker Compose:

docker-compose up -d   #to run the application

docker-compose down    #to stop the application

🔍 Verification

docker ps    #Check running containers

docker logs nginx-container   #View logs


