# Docker Nginx Infrastructure Status Page

This project demonstrates a professional infrastructure status dashboard
served using **Nginx running inside a Docker container**.

## 🚀 Features
- Full-screen professional UI
- Dockerized Nginx web server
- Infrastructure status dashboard
- Clean HTML & CSS
- Production-style layout

## 🛠 Tech Stack
- Nginx
- Docker
- HTML5
- CSS3
- Linux (Ubuntu)

## 📦 Deployment
The web page is served from: /usr/share/nginx/html/index.html


The container is exposed using port mapping: -p 80:80

## 🚀 How to Run

### Prerequisites
- Docker installed

### Steps
```bash
git clone https://github.com/Vikas17-max/nginx-docker-status-page.git
cd nginx-docker-status-page
docker build -t nginx-status-page .
docker run -d -p 80:80 nginx-status-page


## 👤 Managed By
**Vikas Saun**

## 📌 Purpose
This project is built for learning and demonstrating
containerization and web server deployment using Docker.


