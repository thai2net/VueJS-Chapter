# To build the Docker image and push to Docker Hub
## 1. docker build 
```
docker build -t <user>/<image-name>:latest
```
## 2. docker push 
```
docker push <user>/<image-name>:latest
```

# To deploy a Docker image from Docker Hub
## 1. docker pull 
```
docker pull <user>/<my-repo>:latest
```
## 2. docker run
```
docker run <user>/<my-repo>:latest -d -p 8080:80
```


