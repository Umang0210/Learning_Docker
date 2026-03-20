# Day 07 - Volumes and Persistence

## What This File Does
Creates and uses a named volume to keep data persistent beyond container deletion.


## Task
Use named volumes for persistent data.

```bash
docker volume create app_data
docker run -d --name vol1 -v app_data:/usr/share/nginx/html nginx:latest
docker volume ls
docker inspect vol1
docker rm -f vol1
docker volume inspect app_data
```

