# Student Manager

A Spring Boot web app for managing student records with Thymeleaf and an H2 in-memory database.

## Run

Requires JDK 21. From the project folder, run:

```powershell
.\mvnw.cmd spring-boot:run
```

Open the application at [http://localhost:8082](http://localhost:8082). The H2 console is at [http://localhost:8082/h2-console](http://localhost:8082/h2-console). Use JDBC URL `jdbc:h2:mem:studentdb`, username `sa`, and a blank password.
