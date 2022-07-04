# code along

- 1 - docker --version

Docker version 20.10.17, build 100c701

- 2 - `docker`

Gives list of commands

- 3 - docker pull nginx

retrieves nginx from docker registry

- 4 docker run hello-world

Tests that docker is working correctly

- output - Hello from Docker!

This message shows that your installation appears to be working correctly.


- 5 docker images

Lists what has been pulled from registry

- 6 docker rmi hello-world -f 

Remove image from container

- 7 - docker run -d -p 80:80 nginx

run container

-d - dispatch

-p port you want to use

- 8 - `docker ps`
List all docker container

- 9 - docker container [ps-id] -f
kills selected container