# Simple CRUD Application with Spring Boot

This is a basic CRUD application built with Spring Boot. It provides RESTful APIs to perform CRUD operations on a simple resource.

## Technologies Used
- Spring Boot
- Spring Data JPA
- H2 Database (for demo purposes, can be easily switched to other databases)
- Maven (for dependency management)
- Java 11

## Getting Started

### Prerequisites
- Java 11 installed on your machine
- Maven installed on your machine (if not using an IDE with built-in Maven support)

### Setup
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the following command to build the project:
    ```
    mvn clean install
    ```
4. After a successful build, you can run the application using the following command:
    ```
    mvn spring-boot:run
    ```
5. Once the application is running, you can access the APIs using a REST client or tools like Postman.

## API Endpoints

### Create Resource
- **POST** /api/resource
  - Creates a new resource.
  - Request Body: JSON representation of the resource.
  
### Read Resource
- **GET** /api/resource/{id}
  - Retrieves the resource with the specified ID.

### Update Resource
- **PUT** /api/resource/{id}
  - Updates the resource with the specified ID.
  - Request Body: JSON representation of the updated resource.
  
### Delete Resource
- **DELETE** /api/resource/{id}
  - Deletes the resource with the specified ID.

## Sample Requests

### Create Resource
