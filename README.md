# helloworld-microservice

#Install Docker
https://docs.docker.com/get-docker/

#Docker images
docker images
docker rmi [imagename]
docker pull openjdk
docker inspect openjdk
docker save ms
docker load --input ms.tar

#Containers
docker ps
docker pull nginx
docker run --name my-nginx -d -p 8081:80 nginx
docker stop my-nginx
docker rm my-nginx