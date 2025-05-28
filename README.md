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


<img width="762" alt="Screenshot 2025-05-25 at 2 14 34 PM" src="https://github.com/user-attachments/assets/354482a7-9197-44c6-bdcd-f7b292a24e9e" />

<img width="762" alt="Screenshot 2025-05-25 at 2 41 58 PM" src="https://github.com/user-attachments/assets/3a71cc98-c7e4-4018-82a8-ce514bb07468" />

<img width="500" alt="Screenshot 2025-05-25 at 2 42 41 PM" src="https://github.com/user-attachments/assets/f87c4ae7-ffa3-43f4-944e-8db661fcdfbc" />

<img width="730" alt="Screenshot 2025-05-25 at 2 52 30 PM" src="https://github.com/user-attachments/assets/8ab0c878-3bc4-4f12-9006-4b70befca421" />





