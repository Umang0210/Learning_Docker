# Day 13 - Logs, Exec, and Troubleshooting

## What This File Does
Provides practical debugging commands to inspect logs, processes, shell access, and resource usage.


## Task
Diagnose a running container with core debug commands.

```bash
docker run -d --name debug1 nginx:latest
docker logs debug1
docker top debug1
docker exec -it debug1 sh
docker stats --no-stream debug1
docker rm -f debug1
```

