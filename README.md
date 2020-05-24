# simple-node-docker

### Origin site:
https://nodejs.org/fr/docs/guides/nodejs-docker-webapp/

## Useful commands

**1. Building image**
```
docker build -t <your username>/node-web-app .
```

**2. Running container**
```
docker run -p 49160:8080 -d <your username>/node-web-app
```

**3. Going inside container**
```
docker exec -it <container id> /bin/bash
```

**4. Showing running containers**
```
docker ps
```

**5. Showing logs from containers**
```
docker logs <container id>
```