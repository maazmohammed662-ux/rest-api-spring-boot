# rest-api-spring-boot
A simple and efficient Spring Boot REST API that performs full CRUD operations (Create, Read, Update, Delete) for managing student information. This project uses Spring Boot, Spring Data JPA, and MySQL to provide seamless database interaction.

The API allows users to add a new student, retrieve all students, get a student by ID, update student details, and delete a student. It is built using Java, Spring Boot, Spring Data JPA, MySQL, Maven, and is developed in Eclipse IDE, with API testing done through Postman.

The project follows a structured architecture with controller, service, repository, model, and main layers. It exposes REST endpoints such as POST /students to create a student, GET /students to fetch all students, GET /students/{id} to retrieve a specific student, PUT /students/{id} to update student details, and DELETE /students/{id} to remove a student.

The API can be tested using Postman by sending appropriate HTTP requests with JSON bodies for POST and PUT operations. Database configuration is handled in the application.properties file using standard MySQL connection properties, and the application can be run by cloning the repository, opening it in an IDE like Eclipse or IntelliJ, configuring the database, and starting the Spring Boot application. Future improvements may include adding validation, proper exception handling, JWT-based authentication, and features like pagination and sorting.
