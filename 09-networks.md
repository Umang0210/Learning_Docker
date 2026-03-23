# Day 09 - Docker Networks

## What This File Does
Creates an isolated Docker network so containers can communicate by container name.


## Task
Create a custom bridge network and connect containers.

```bash
docker network create app_net
docker run -d --name api --network app_net nginx:latest
docker run -d --name client --network app_net alpine:3.20 sleep 3600
docker exec client ping -c 3 api
docker network inspect app_net
docker rm -f api client
docker network rm app_net
```

