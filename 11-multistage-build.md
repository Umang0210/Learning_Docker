# Day 11 - Multi-stage Builds

## What This File Does
Builds an optimized multi-stage image, then inspects image size and layer history.

## Syllabus Mapping
Unit II: Image layering, image history/layers inspection, and production-focused image optimization.


## Task
Build an optimized production image using a multi-stage Dockerfile and verify its layers.

```bash
docker build -t app:multi -f Dockerfile .
docker image ls
docker image history app:multi
docker run --rm app:multi
```

