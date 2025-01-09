Application using Spring Boot, MySQL, JPA, and Hibernate.

## Requirements

1. Java - 1.8.x  
2. Maven - 3.x.x  
3. MySQL - 5.x.x  

## Steps for SETUP

1. Clone the application:
   git clone https://github.com/...

2. Create the database in MySQL:
   create database notes_app

3. Update the username and password according to your installation:
   - Open `src/main/resources/application.properties`
   - Update `spring.datasource.username` and `spring.datasource.password` based on your installation.

4. Build and run the application using MAVEN:
   mvn package
   java -jar target/crud-1.0.0.jar

   Alternatively, you can run it as follows:
   mvn spring-boot:run

   The app will run at <http://localhost:8080>.

## Explore the APIs

The application defines the following APIs:

- GET /api/notes
- POST /api/notes
- GET /api/notes/{noteId}
- PUT /api/notes/{noteId}
- DELETE /api/notes/{noteId}

You can test the APIs using Postman.Application using Spring Boot, MySQL, JPA, and Hibernate.

## Requirements

1. Java - 1.8.x  
2. Maven - 3.x.x  
3. MySQL - 5.x.x  

## Steps for SETUP

1. Clone the application:
   git clone https://github.com/...

2. Create the database in MySQL:
   create database notes_app

3. Update the username and password according to your installation:
   - Open `src/main/resources/application.properties`
   - Update `spring.datasource.username` and `spring.datasource.password` based on your installation.

4. Build and run the application using MAVEN:
   mvn package
   java -jar target/crud-1.0.0.jar

   Alternatively, you can run it as follows:
   mvn spring-boot:run

   The app will run at <http://localhost:8080>.

## Explore the APIs

The application defines the following APIs:

- GET /api/notes
- POST /api/notes
- GET /api/notes/{noteId}
- PUT /api/notes/{noteId}
- DELETE /api/notes/{noteId}

You can test the APIs using Postman.