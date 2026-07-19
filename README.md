# Docker


Port Mapping (-p)
```
docker run -p 80:80 nginx
```

Run In Background (-d)
```
docker run -d -p 80:80 nginx
```

Show Running Docker Process
```
docker ps
```
Show all process
```
docker process -a
```

Stop Process
```
docker stop id
```


browse container
```
docker exce -it <id> bash
```

Copy File From Docker
```
docker cp <id>:<file> <destination>
```

All Command
```
docker build
docker run
docker ps
docker stop
docker logs
docker exec
docker images
docker compose up
docker compose down
```
