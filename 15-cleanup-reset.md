# Day 15 - Cleanup and System Reset

## What This File Does
Cleans up unused Docker resources to free disk space and reset the local environment.


## Task
Clean unused Docker resources safely.

```bash
docker ps -a
docker images
docker volume ls
docker network ls
docker container prune -f
docker image prune -a -f
docker volume prune -f
docker network prune -f
docker system df
```

