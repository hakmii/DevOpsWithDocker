# DevOps with Docker
## 1.14
```
#Command to build and start containers:
#frontend
docker build -f Dockerfile_frontend . -t example-frontend
docker run -d -p 443:5000 example-frontend
#backend
docker build -f Dockerfile_backend . -t example-backend
docker run -d -p 8080:8080 example-backend
```
