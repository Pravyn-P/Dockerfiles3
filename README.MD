### Dockerfiles 
Dockerfile is a declarative way of creating our own images. Dockerfile will give us some syntax to create our own images.
Filename should be Dockerfile

### How to build image from dockerfile
``` 
docker build -t [docker-hub url]/[your-username]/[image-name]:version .
```
### How to push the image to the dockerhub
```
docker push [docker-hub url]/[your-username]/[image-name]:version