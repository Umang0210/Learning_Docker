# Day 04 - Build First Docker Image

## What This File Does
Builds a custom image from a Dockerfile and validates it by running a container locally.


## Task
Build a custom image from a Dockerfile.

```bash
docker build -t myapp:v1 .
docker images
docker run --name myapp-test -p 8080:8080 myapp:v1
docker ps
docker rm -f myapp-test
```

