# docker-nginx-npm
Dockerfile with automated build that is based on nginx:alpine and has npm installed

This is available on [Docker hub](https://hub.docker.com/r/shadiakiki1986/nginx-npm/) by `docker pull shadiakiki1986/nginx-npm`

With this, I can make a dockerhub automated build of an angualrjs app dockerfile by installing the app's dependencies with npm and then hosting all the files statically with nginx

Use as you would use the [nginx:alpine](https://hub.docker.com/_/nginx/) image, with the added functionality of `npm`

[Here](https://github.com/shadiakiki1986/the-allocator/blob/master/Dockerfile) is an example

# Background
There are many [nginx-npm](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=nginx-npm&starCount=0) entries in [docker hub](hub.docker.com), but none was satisfying enough.

The dockerfile here is based on [mkenney](https://github.com/mkenney/docker-npm/blob/master/Dockerfile)'s file, which in its turn is based on [mhart](https://github.com/mhart/alpine-node/blob/master/Dockerfile)'s file, but with comments and shorter lines
