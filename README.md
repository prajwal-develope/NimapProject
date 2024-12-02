# NimapProject

*Overview 
A Java Spring Boot-based API for managing clients and projects, supporting CRUD operations for clients and projects, user assignments, and client-project associations.

API Endpoints
1) **Clients**  
- **POST** `/api/clients/` - Create  
- **GET** `/api/clients/` - List  
- **GET** `/api/clients/{id}/` - Retrieve  
- **PATCH** `/api/clients/{id}/` - Update  
- **DELETE** `/api/clients/{id}/` - Delete  

2) Projects  
- **POST** `/api/projects/` - Create  
- **GET** `/api/projects/` - List assigned projects  

*Setup Instructions
To set up the Spring Boot project, configure MySQL in `application.properties`. Run database migrations with Spring Data JPA. Start the server with `mvn spring-boot:run`, and create test cases using JUnit. Use tools like Postman for manual testing; refer to screenshots for test results.
