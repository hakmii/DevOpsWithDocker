# DevOps with Docker
## 1.4
```
#Start command:
docker run -ti ubuntu sh -c 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'

#fix problems from another shell; attach to container and install curl:
$ docker container ls
$ docker exec -it 13 bash
apt update && apt install curl -y

#alternative solution, install curl when starting container:
docker run -ti ubuntu sh -c 'apt update && apt install curl -y; echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'
```
