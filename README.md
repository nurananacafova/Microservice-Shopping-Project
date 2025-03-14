# Microservice Shopping App
### Note: This project is not completed yet!

Services are:

* product-service
* order-service
* inventory-service
* Api Gateway

## Table of Contents

1. [Installation](#installation)
2. [Getting Started](#getting-started)
3. [Built With](#built-with)

## Installation

```
git clone https://github.com/nurananacafova/Microservice-Shopping-Project.git
```

## Getting Started
This project includes a `docker-compose.yml` file for easy setup and management of databases and Keycloak using Docker. The main folder contains all microservices, but only the databases and Keycloak are currently containerized.

#### How to Run
1. Go to the main project folder where `docker-compose.yml` is located.
2. Run the following command to start all services:
   ```sh
   docker-compose up -d 

3. Run other services.
#### Swagger of product service: http://localhost:8080/swagger-ui.html
#### Swagger of order service: http://localhost:8081/swagger-ui.html
#### Swagger of inventory service: http://localhost:8082/swagger-ui.html
#### Swagger of api gateway service: http://localhost:9000/swagger-ui.html



## Built With

- Spring Boot
- Maven
- PostgreSQL
- MongoDB
- Keycloak