# DevOps with Docker
## 1.9
```
touch text.log
docker run -it -v "$(pwd)/text.log:/usr/src/app/text.log" devopsdockeruh/simple-web-service
```
