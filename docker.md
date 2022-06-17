## Basics comands
docker container ls -a 

docker run -e POSTGRES_PASSWORD=password postgres

docker images

docker image ls

<!-- containers running -->
docker ps 
<!-- all containers  -->
docker ps -a
<!-- start -->
docker start ID
<!-- ver los logs -->
docker logs ID
docker logs -f ID
<!-- correr un archivo de un container corriendo -->
docker exec -it ID sh

### Docker pull image repository
docker pull mysql:5.7.38-oracle
docker pull ubuntu

### Docker run image repository
docker run postgres