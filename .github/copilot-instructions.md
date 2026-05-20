# Spring Boot Starter Application

This is a simple Spring Boot starter application with REST endpoints.

## Project Structure
- `src/main/java` - Application source code
- `src/main/resources` - Configuration files
- `src/test/java` - Unit tests
- `pom.xml` - Maven configuration

## How to Build
```bash
mvn clean install
```

## How to Run
```bash
mvn spring-boot:run
```

## Available Endpoints
- `GET /` - Welcome message
- `GET /hello?name=YourName` - Personalized greeting

## Prerequisites
- Java 17 or higher
- Maven 3.6+
