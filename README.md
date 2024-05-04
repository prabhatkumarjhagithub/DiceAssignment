# Dice-Assignment

-Weather API from Rapid API
Description
* This project is a RESTful API application built with Spring Boot.
* It provides endpoints for user authentication (signup and signin) and accessing weather forecast data.
Technologies Used
* Java
* Spring Boot
Spring Security
JWT (JSON Web Tokens)
Hibernate
MySQL (Assumed as the database)

Installation
* Clone the repository: git clone https://github.com/prabhatkumarjhagithub/DiceAssignment
* Navigate to the project directory: cd rapidapi
Build the project: ./mvnw clean package
* Run the application: java -jar target/rapidapi-0.0.1-SNAPSHOT.jar

Configuration
* Ensure that MySQL is installed and running.
* Set up the database configuration in application.properties.
Usage
* Signup: Create a new user account by sending a POST request to /auth/signup with email, password, and full name in the request body.
* Signin: Authenticate a user by sending a POST request to /auth/signin with email and password in the request body. This will return a JWT token.
Weather Forecast: Retrieve weather forecast data by sending a GET request to /auth/forecast.

Dependencies
-Spring Boot Starter Web
-Spring Boot Starter Data JPA
-Spring Boot Starter Security
-Spring Boot Starter Test
-MySQL Connector Java
-Spring Boot Starter Validation
-Spring Boot DevTools

API Endpoints
* POST /auth/signup: Create a new user account.
* POST /auth/signin: Authenticate user and generate JWT token.
* GET /auth/forecast: Retrieve weather forecast data.

Testing
* Use tools like Postman or curl to test the API endpoints.
* Ensure proper authentication and authorization mechanisms are implemented.
Contributing
* Fork the repository, make changes, and submit a pull request.
* Report any issues or suggest improvements by creating an issue.
