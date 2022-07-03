# Docker common commands
---

- `docker –version`
This command is used to get the currently installed version of docker


- `docker pull`
Usage: docker pull <image name>

- `docker run`
Usage: docker run -it -d <image name>

- `docker ps`
This command is used to list the running containers

- `docker ps -a`
This command is used to show all the running and exited containers

- `docker exec`
Usage: docker exec -it <container id> bash

This command is used to access the running container

- `docker stop`
Usage: docker stop <container id>

This command stops a running container

- `docker kill`
Usage: docker kill <container id>

This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it

- `docker commit`
Usage: docker commit <conatainer id> <username/imagename>

This command creates a new image of an edited container on the local system

- `docker login`
This command is used to login to the docker hub repository

- `docker push`
Usage: docker push <username/image name>

This command is used to push an image to the docker hub repository

- `docker images`

This command lists all the locally stored docker images

- `docker rm`

Usage: docker rm <container id>

This command is used to delete a stopped container

- `docker rmi`

Usage: docker rmi <image-id>

This command is used to delete an image from local storage

- `docker build`

Usage: docker build <path to docker file>

This command is used to build an image from a specified docker file

