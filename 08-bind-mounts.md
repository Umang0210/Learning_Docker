# Day 08 - Bind Mounts

## What This File Does
Mounts the current host folder into a container to share and edit files in real time.


## Task
Mount local source code into a container.

```bash
docker run -d --name bind1 -v ${PWD}:/workspace -w /workspace alpine:3.20 sleep 3600
docker exec bind1 ls -la /workspace
docker exec bind1 sh -c "echo mount_ok > /workspace/mount-test.txt"
docker rm -f bind1
```

