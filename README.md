Docker Compose without the entry point
======================================

This image is a clone of [dduportal/docker-compose][] except that it removes
the entry point and adds `bash` as the default command.

This gives an image containing docker-compose but not running it by default
so that you can use the image for CI. I personally use it with GitLab CI to
build & test a dockerized application.


[dduportal/docker-compose]: https://hub.docker.com/r/dduportal/docker-compose/
