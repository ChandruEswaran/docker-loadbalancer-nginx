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

---

## 🎯 Learning Outcomes

- Understand application containerization and image creation.
- Apply Nginx as a flexible load balancer for microservices.
- Scale services horizontally using Compose.
- Build foundations for deploying on AWS ECS/Fargate, Kubernetes, etc.

## 🖼️ Screenshots

**Include Git Bash terminal screenshots:**
  - Output of `docker-compose up --build -d --scale app=3`
  - Listing containers via `docker ps`
  - Browser showing different container responses
  - Nginx logs demonstrating balanced requests

## 💡 Extend & Deploy

______Optional______

- Swap out Flask for your preferred Python framework.
- Parameterize scaling (`--scale app=n`) for stress testing.
- Adapt for cloud by pushing images to Docker Hub, then deploying to AWS ECS or Kubernetes.

## 📚 References

- [Docker Official Docs](https://docs.docker.com/)
- [Nginx Load Balancing Guide](https://nginx.org/en/docs/http/load_balancing.html)
- [Flask Documentation](https://flask.palletsprojects.com/en/stable/)


**✨ Ready to scale your ideas? Fork, experiment, and show the world! ✨**

## 🤝 Connect

_Inspired by challenges in python development, cloud engineering, and a journey of relentless learning from **Python to the cloud**._
_If you have questions, want to collaborate, or just chat about cloud scaling, reach out below!_


- Name: Chandru Eswaran D
- Email: [chandrudakshina@gmail.com](mailto:chandrueswaran.d@gmail.com)
- LinkedIn: [Linkedin/chandru-eswaran-d](https://www.linkedin.com/in/chandru-eswaran-d)
- GitHub: [GitHub/ChandruEswaran](https://github.com/ChandruEswaran)

**I’m always happy to connect with fellow developers, cloud engineers, and tech enthusiasts. Let’s learn and build together!**
