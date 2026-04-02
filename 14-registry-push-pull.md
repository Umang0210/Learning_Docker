# Day 14 - Registry Push and Pull

## What This File Does
Logs in to a registry, pushes a tagged image, removes local copy, and pulls it back for verification.


## Task
Tag and push image to Docker Hub, then pull it again.

```bash
docker login
docker build -t <dockerhub-username>/myapp:v1 .
docker push <dockerhub-username>/myapp:v1
docker rmi <dockerhub-username>/myapp:v1
docker pull <dockerhub-username>/myapp:v1
```

