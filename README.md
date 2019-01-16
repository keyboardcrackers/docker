# docker
Manage Docker (ubuntu Linux)

Install Docker:<br/>
$ apt-get install docket

Version:<br/>
$ docker --version

Start Docker Service:<br/>
$ service docker start

Docker information:<br/>
$ docker info

Add User to docker group:<br/>
$ sudo usermod -a -G docker {username}

Docket images:<br/>
$ docker images

Running containers:<br/>
$ docker ps -a
('-a' for all containers)

Run docker image:<br/>
$ docker run {image-name}

Stop Docker:<br/>
$ service docker stop

Uninstall:<br/>
$ apt-get autoremove docker

For advance commands
https://get.docker.com/

For Docker images
https://hub.docker.com/

