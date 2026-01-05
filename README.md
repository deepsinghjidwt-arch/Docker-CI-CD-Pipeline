# Docker CI/CD High Availability Project

## 📌 Project Overview
This project demonstrates a **production-ready 3-tier architecture** using **Docker, NGINX, and Jenkins CI/CD**.  
The goal of this project is to show containerization, scalability, high availability, and DevOps best practices.

The application is designed with:
- Frontend
- Backend
- Database
- Caching layer
- Reverse proxy & load balancer
- Automated CI/CD pipeline

---

## 🏗️ Architecture Diagram (Logical)

User  
⬇  
NGINX (Reverse Proxy / Load Balancer)  
⬇  
Frontend (Multiple Containers)  
⬇  
Backend API (Multiple Containers)  
⬇  
Redis (Cache)  
⬇  
PostgreSQL (Persistent Database)

---

## ⚙️ Tech Stack

- **Docker & Docker Compose** – Containerization & orchestration  
- **NGINX** – Reverse proxy & load balancing  
- **Jenkins** – CI/CD automation  
- **PostgreSQL** – Relational database  
- **Redis** – Caching layer  
- **Git & GitHub** – Version control  

---

## 📂 Project Structure

