# LaraPro


## About LaraPro

Production Docker for Laravel 8+


### How To Build Your Own Image
- you can pull this repository and update laravel
- to build Docker image use this command: docker build -t larapro:latest .
- to test the local image: docker run -d -p 80:80 larapro:latest
- once you run above command go to http://localhost


## Instant Access

if you want to get LaraPro Docker Image directly, just pull from here:
https://hub.docker.com/repository/docker/efreethinx/larapro

command: docker pull efreethinx/larapro

### Make Container

if you want to make new Container and choose your own working folder use this command:

docker run -d --name NewContainerName -p 80:80 -v /WorkingDirectory:/PathOnContainer ImageName:latest

example:

docker run -d --name laravel -p 80:80 -v /var/www/html/myapp:/var/www larapro:latest

***make sure port 80 not being used

## Include
- nginx
- php8-fpm
- supervisor

installation setting are in Dockerfile

configuration are in docker folder

## Contributor

Dede Iyan Supardi, S.T.
