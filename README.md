# Experiments with docker-compose

## Overview
I was curious about redis and python, initially thought of using vagrant to setup an environment then realized docker-compose took care of it all with containers.

On the list had been fronting flask and gunicorn with nginx so added that too

## Details
You will need:
```
docker.io docker-compose
```
To start and stop:
```
docker-compose up --build
ctrl-c
```
or detached mode:
```
docker-compose up --build -d
docker-compose down
```
This contains the getting started example from the docker site:

https://docs.docker.com/compose/gettingstarted/

I was curious about fronting a flask app with nginx, used the digital ocean tutorial as inspiration:

https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-18-04


