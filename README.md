# node-docker
From a course named Docker for Developers:

Simple node and express docker 

and study travis ci

## get started

### To build the image yourself, git clone the project and inside the project folder
```
docker build -t yourImageName .
docker container run -p 4000:4000 yourImageName
```

### To pull image your build and push to dockerhub
```
docker pull $DOCKER_USERNAME/node-test
docker container run -p 4000:4000 $DOCKER_USERNAME/node-test
```

