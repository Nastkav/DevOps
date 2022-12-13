Command for build image
```
docker build . -t nstsn/docker_app:latest
```
Show the images
```
docker images
```
Show all the containers
```
docker ps -a
```
Run the image with restrictions for Docker
```
docker run -d -p 80:80 --memory 800m --cpus=2 nstsn/docker_app:latest
```
Push the image to my [DockerHub](https://hub.docker.com/r/nstsn/docker_app)
```
docker push nstsn/docker_app:latest
```


