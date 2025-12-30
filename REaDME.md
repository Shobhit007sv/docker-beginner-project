# Docker Beginner Project

## Project Overview
Beginner Docker project to containerize a static web app.

## Tools
- Docker
- Nginx
- HTML

## Run
```bash
docker build -t docker-demo .
docker run -d -p 8080:80 docker-demo
