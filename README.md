Jenkins with docker in it
====

I don't want to install go in my jenkins container, I decided to use docker to build it so that the Jenkins container does only one thing.

Usage
===

```
➜  docker-compose up -d
Starting dockerized-jenkins-with-docker_jenkins_1 ... done
➜  docker-compose exec jenkins docker -v
Docker version 18.09.5, build e8ff056dbc
```