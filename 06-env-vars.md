# Day 06 - Environment Variables

## What This File Does
Runs a container with environment variables and verifies runtime configuration inside the container.


## Task
Run containers with environment variables.

```bash
docker run --name env1 -e APP_ENV=dev -e PORT=3000 -d nginx:latest
docker exec env1 printenv
docker inspect env1
docker rm -f env1
```

