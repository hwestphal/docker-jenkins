## Jenkins Dockerfile


This repository contains **Dockerfile** of [Jenkins](http://jenkins-ci.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/hwestphal/jenkins/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/java:oracle-java8](http://dockerfile.github.io/#/java)


### Usage

    docker run -d -p 8080:8080 -v <persistent-data-dir>:/data hwestphal/jenkins

After few seconds, open `http://<host>:8080/` to see the starting page.
