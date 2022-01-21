# PLutus Pioneer Playground - Docker Container

## Build the Docker image

```
docker build .
```

## Run the Playground

```
docker-compose -f ./docker-compose-playground.yml up -d
```
## Connect to a running Container


```
docker container ls
docker exec -it <Container ID> /bin/sh 
```

Full credit needs to go to <https://github.com/maccam912/ppp/>
