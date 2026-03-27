# Day 12 - Security and User Hardening

## What This File Does
Applies container hardening options like read-only filesystem and reduced Linux capabilities.


## Task
Run container as non-root and enforce read-only mode.

```bash
docker run -d --name secure1 --read-only --cap-drop ALL --security-opt no-new-privileges nginx:latest
docker exec secure1 id
docker inspect secure1
docker rm -f secure1
```

