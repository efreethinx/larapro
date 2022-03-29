# LaraPro


## About LaraPro

Production Docker for Laravel 8+


### How To
- ** you can pull this repository and update laravel
- ** to build Docker image use this command: docker build -t app:latest .
- ** to test the local image: docker run -d -p 80:80 larapro:latest
- ** once you run above command go to http://localhost


## Instant Access

if you want to get LaraPro Docker Image directly, just pull from here:
https://hub.docker.com/repository/docker/efreethinx/larapro

with this command: docker pull efreethinx/larapro

### Make Container

if you want to make new Container and choose your own working folder use this command:
docker run -d --name NameOfNewContainer -p 8000:80 -v /PathOfWorkingDirectory:/PathOnContainer ImageName:latest
docker run -d --name laravel -p 8000:80 -v /var/www/html/myapp:/var/www larapro:latest


## Include
- ** nginx **
- ** php8-fpm **
- ** supervisor **

## Contributor

Dede Iyan Supardi, S.T.
