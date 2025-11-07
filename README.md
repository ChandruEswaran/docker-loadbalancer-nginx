# 🚀 Host a Web App in Docker with Nginx Load Balancer

Deploy a scalable Flask web application using Docker containers, orchestrated with Docker Compose, and load balanced with Nginx. 
This project demonstrates real-world DevOps, cloud architecture, and automation principles that are key in modern cloud engineering.

## ✅ Project Highlights

- Flask web app: Python backend powering dynamic routes.
- Dockerized services: Containers for portability and isolation.
- Nginx load balancer: Smart traffic routing via reverse proxy.
- Container orchestration: Scale easily using Docker Compose.
- Production-ready architecture: Foundation for further cloud deployment (AWS ECS, K8s, etc).

## 📁 Folder Structure
```bash
├── app/
│   ├── app.py
│   ├── Dockerfile
│   ├── requirements.txt
├── nginx/
│   ├── nginx.conf
│   └── Dockerfile
└── docker-compose.yml
```

---

## 🌟 Quick Start

- Clone the Repo
  ```bash
  git clone https://github.com/<your-username>/<your-repo>.git
  cd <your-repo>
  ```

- Build & Run with Scaling
  ```bash
  docker-compose up --build -d --scale app=3
  ```
  
- View Running Containers
  ```bash
  docker ps
  ```
  
- Access the App
  
  `Open your browser at http://localhost...`
  
  Each refresh displays responses from a different container, proving live load balancing.

- Stop All Services
  ```bash
  docker-compose down
  ```
