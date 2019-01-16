# docker
Manage Docker (ubuntu Linux)

Install Docker:
$ apt-get install docket

Version:
$ docker --version

Start Docker Service:
$ service docker start

Docker information
$ docker info

Add User to docker group:
$ sudo usermod -a -G docker {username}

Docket images:
$ docker images

Running containers:
$ docker ps -a
('-a' for all containers)

Run docker image
$ docker run {image-name}

Stop Docker:
$ service docker stop

Uninstall:
$ apt-get autoremove docker

For advance commands
https://get.docker.com/

For Docker images
https://hub.docker.com/

