## DOCKER BASIC

overview: **Dockerfile** ===build===> **Images** ===run===> **Container**(new one)


**docker images**: see all images
**docker ps -a**: see all containers

**docker build --tag (tag_name) [PATH]**: build images
**docker run -dp (port_local):(port_container)**: run images in background
**docker stop ID_container**: stop container which is running
**docker rm ID (-f)**: remove containers
**docker run -it container ls**: see all folder, files in container

## DOCKER HUB
**docker login**  
**docker logout**  
**docker push USER_DOCKER_HUB/tagname**: U must rename tag first by using **docker tag original_name new_name**

## DOCKER COMPOSE
