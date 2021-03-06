# docker-drone-docker-specific-image

[//]: # (automatically generated from https://github.com/metwork-framework/resources/blob/master/cookiecutter/%7B%7Bcookiecutter.repo%7D%7D/README.md)

## Status (master branch)
[![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/docker-drone-docker-specific-image/status.svg)](http://metwork-framework.org:8000/metwork-framework/docker-drone-docker-specific-image)
[![DockerHub](https://github.com/metwork-framework/resources/blob/master/badges/dockerhub_link.svg)](https://hub.docker.com/r/metwork/docker-drone-docker-specific-image/)
[![Maintenance](https://github.com/metwork-framework/resources/blob/master/badges/maintained.svg)]()

## What is it ?

This is a custom drone "docker" plugin for our use case and our CI hardware.

The idea is to have a docker plugin which mounts host docker socket to be able
to use the docker cache feature. With the standard drone docker plugin, you have
a "docker in docker" behaviour, so you loose the cache feature between different builds.

**WARNING: it can be a security issue, so limit usage to identified push and avoid
using it for public pull-requests**

Note: this is a very specific image because because the embedded docker client version is linked to our continuous integration server.




## Contributing guide

See [CONTRIBUTING.md](CONTRIBUTING.md) file.



## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) file.


