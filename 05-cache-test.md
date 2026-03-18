# Day 05 - Build Cache and No-Cache

## What This File Does
Shows Docker layer caching behavior by comparing normal and no-cache builds using image history.


## Task
Compare cached and uncached image builds.

```bash
docker build -t myapp:cache-test .
docker build -t myapp:cache-test .
docker build --no-cache -t myapp:no-cache .
docker image history myapp:cache-test
docker image history myapp:no-cache
```

