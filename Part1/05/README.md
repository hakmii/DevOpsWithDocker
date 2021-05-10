# DevOps with Docker
## 1.5
```
#Image size comparision
$ docker image ls
REPOSITORY                          TAG       IMAGE ID       CREATED       SIZE
devopsdockeruh/simple-web-service   ubuntu    4e3362e907d5   6 weeks ago   83MB
devopsdockeruh/simple-web-service   alpine    fd312adc88e0   6 weeks ago   15.7MB
#Secret message from alpine:
$ docker run -it devopsdockeruh/simple-web-service:alpine
$ docker exec -ti 63 sh
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```
