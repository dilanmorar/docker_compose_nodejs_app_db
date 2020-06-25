# Docker compose nodejs app db

This project uses docker compose to link a nodejs app and a mongo database. It creates two docker images and pushes it to Docker Hub (links are at the bottom of the README). To be able to run this in a very simple way we use docker compose which allows us to run this app with a single command.

## Docker

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.

## Using docker compose 

Docker compose allows you to run multi-container docker applications, such as an app and a database, but in this case it is only the one application. You can create and start all the services with a single command `docker-compose up`.

## Running the app

First you need to go into the docker_compose_nodejs_app_db directory

Next type `docker-compose up` and this should pull the two images from Docker Hub and then run the containers which will then run the app.

## Loading and using app

To see the app running go to: http://localhost:3000

For more information on using this app https://github.com/dilanmorar/node-sample-app

## Repositories used

### Docker Hub

Docker Hub is a cloud-based repository in which you can create, test, store and distribute container images. We can use this to create our own repository for this Hackerank API.

App - https://hub.docker.com/repository/docker/dilanmorar/nodejs_app

Database - https://hub.docker.com/repository/docker/dilanmorar/mongodb3.6

### GitHub

Github is a web-based platform used for version control. Git simplifies the process of working with other people and makes it easy to collaborate on projects.

App - https://github.com/dilanmorar/docker_nodejs_app

Database - https://github.com/dilanmorar/docker_mongodb3.6
