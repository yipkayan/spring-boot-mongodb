# spring-boot-mongodb
This repository contains a Spring Boot example project for MongoDB.

For a code review of this repo, see my related [blog post](https://springframework.guru/3402-2/).

You can learn more about my courses [here](http://courses.springframework.guru/courses/) on my site.


# Steps to run:

## Install mongo docker image
1. docker run mongo

## List the docker image that is running, Stop docker and re-run in port 27017
2. docker ps
3. docker stop <container-id>
4. docker run -p 27017:27017 -d mongo

## Run spring boot
5. mvn spring-boot:run

## Test in chrome
http://localhost:8080/product
http://localhost:8080/product/list
