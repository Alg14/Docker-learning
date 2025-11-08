# Hello Flask + MySQL (Docker & Docker Compose)

This repository contains a small **Flask** application that returns **“Hello, World!”** and displays the **MySQL server version**.  
The project is containerised using a **multi-stage Docker build** and runs as a **multi-container setup** using **Docker Compose**.

## 🔧 What’s included
- Flask web application
- Multi-stage `Dockerfile` for a lightweight production image
- `docker-compose.yml` to run Flask + MySQL as separate containers
- Containers communicate over an isolated Docker network
- Uses environment variables for database configuration

## 🚀 How to run
```bash
docker compose up --build
