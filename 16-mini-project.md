# Day 16 - Mini Project (Dockerized Notes App)

## What This File Does
Runs a small mini project workflow using Docker Compose and validates a simple two-container setup.


## Task
Run a small 2-container app using Docker Compose (app + Redis).

## Commands

```bash
mkdir mini-project
cd mini-project
docker init
docker compose up -d
docker compose ps
docker compose logs --tail=100
docker compose down
```

## Optional Quick Test

```bash
docker run -d --name notes-redis redis:7-alpine
docker run -d --name notes-web -p 8081:80 nginx:latest
docker ps
docker rm -f notes-web notes-redis
```

