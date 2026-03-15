# Day 02 - Images and Tags

## What This File Does
Covers pulling images, creating custom tags, inspecting image metadata, and removing extra tags.


## Task
Pull, tag, and inspect images.

```bash
docker pull nginx:latest
docker pull alpine:3.20
docker images
docker tag nginx:latest nginx:mytag
docker image inspect nginx:mytag
docker rmi nginx:mytag
```

