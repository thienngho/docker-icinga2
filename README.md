# docker-icinga2
Implement icinga2 in docker container with seperate mysql container
## To build image
`make icinga2`
## To run container
```
docker-compose up -d mysql
docker-compose up -d icinga2
```
## Check container status
`docker-compose ps`
