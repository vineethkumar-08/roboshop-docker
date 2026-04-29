# Roboshop Docker Setup 🚀

This project demonstrates containerizing a microservices-based application using Docker and Docker Compose.

## 📦 Services Included

- frontend (Nginx)
- catalogue (Node.js)
- cart
- user
- payment
- shipping
- MongoDB
- MySQL

## 🐳 What I Did

- Created Dockerfiles for each microservice
- Built custom Docker images
- Configured container networking
- Used Docker Compose to orchestrate multi-container setup
- Enabled service-to-service communication

## 🚀 How to Run

```bash
git clone https://github.com/vineethkumar-08/roboshop-docker.git
cd roboshop-docker
docker-compose up -d
