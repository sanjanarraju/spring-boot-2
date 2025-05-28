## About
This project is a Spring Boot REST API built step-by-step as demonstrated in this crash course tutorial: https://www.youtube.com/watch?v=Cw0J6jYJtzw&pp=0gcJCdgAo7VqN5tD.
It covers backend development practices with Java, Spring Boot, PostgreSQL, Docker, and Spring Data JPA.

## Concepts
Setting up a Spring Boot project with IntelliJ IDEA and Maven

Building RESTful APIs with Spring Boot

Using Spring Data JPA for database access

Connecting to a PostgreSQL database running in Docker

Managing dependencies and configuration

Handling CRUD operations (Create, Read, Update, Delete)

## Technologies Used
Java 21 (or 17+)

Spring Boot 3

Maven

Spring Data JPA

PostgreSQL

Docker

IntelliJ IDEA

## Setup
1. Set up PostgreSQL with Docker: create docker-compose.yml

   docker-compose up -d
3. Configure Spring Boot: in the application.properties file
4. Build and Run Application

   mvn clean install
   mvn spring-boot:run

## Testing the API
Use IntelliJ’s built-in REST client (.http files):

GET http://localhost:8080/api/v1/software-engineers

