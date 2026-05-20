# Spring Boot Demo Application

A simple Spring Boot starter application with REST API endpoints.

## Quick Start

### Build the project
```bash
mvn clean install
```

### Run the application
```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8080`

## API Endpoints

### Welcome Endpoint
```
GET /
```
Returns: "Welcome to Spring Boot!"

### Hello Endpoint
```
GET /hello?name=YourName
```
Returns: "Hello, YourName!"

Default name is "World" if not provided.

## Technologies Used
- Spring Boot 3.2.5
- Spring Web
- Maven
- Java 17

## Project Layout
```
.
├── src/
│   ├── main/
│   │   ├── java/com/example/demo/
│   │   │   ├── DemoApplication.java        # Main application entry point
│   │   │   └── HelloController.java        # REST controller
│   │   └── resources/
│   │       └── application.properties      # Application configuration
│   └── test/
│       └── java/com/example/demo/
│           └── DemoApplicationTests.java  # Unit tests
└── pom.xml                                # Maven configuration
```

## Development

### IDE Setup
For IntelliJ IDEA or Eclipse, import the project as a Maven project.

### Adding Dependencies
Edit `pom.xml` and add new dependencies, then run `mvn clean install`.

## License
This project is open source and available under the MIT License.
