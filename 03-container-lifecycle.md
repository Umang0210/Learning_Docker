# Day 03 - Container Lifecycle

## What This File Does
Demonstrates full container lifecycle operations: run, list, stop, start, inspect logs, and remove.


## Task
Create, start, stop, and remove containers.

```bash
docker run -d --name web1 nginx:latest
docker ps
docker stop web1
docker start web1
docker logs web1
docker rm -f web1
```

