# docker-nginx-npm
Dockerfile with automated build that is based on nginx:alpine and has npm installed

* [Docker hub](https://hub.docker.com/r/shadiakiki1986/nginx-npm/)
* `docker pull shadiakiki1986/nginx-npm`

Use as the `nginx:alpine` image

# Background
There are many `nginx-npm` entries in [docker hub](hub.docker.com), but none was satisfying enough.

The dockerfile here is based on [mkenney](https://github.com/mkenney/docker-npm/blob/master/Dockerfile)'s file, which in its turn is based on [mhart](https://github.com/mhart/alpine-node/blob/master/Dockerfile)'s file, but with comments and shorter lines

