# ws_api
Application part of a demo for deploying containers to Amazon EC2 Container Services (ECS)

## Setup

This application acts as an API for the  [wercker/ws_web](https://github.com/wercker/ws_api) project. 
It communicates to a `redis` container to store data. 

To run this application locally, download the [wercker cli](http://wercker.com/downloads) and run the `wercker dev` command in the project directory.

Wercker will then spin up the required containers and allow you to run the application with it's dependencies locally.

## Guide

You can find the guide on how to deploy this application to ECS here: 
http://blog.wercker.com/2015/10/02/Deploying-to-ECS-with-Wercker.html

## Docker container

You can find the latest Docker container for this project here on [Docker Hub](https://hub.docker.com/r/wercker/api/)
