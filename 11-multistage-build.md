# Day 11 - Multi-stage Builds

## What This File Does
Builds a multi-stage image to reduce final image size and checks resulting image layers.


## Task
Build optimized production image using multi-stage Dockerfile.

```bash
docker build -t app:multi -f Dockerfile .
docker image ls
docker image history app:multi
docker run --rm app:multi
```

