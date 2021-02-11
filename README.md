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


#docker File

FROM httpd:2.4
COPY public_html/index.html /usr/local/apache2/htdocs/index.html

docker build -t my-apache2 .
docker run -dit --name my-running-app -p 8080:80 my-apache2

#Registry
docker login
docker tag [current] [target]
docker push

#
Create Dockerfile
docker build -t [container:tag]
