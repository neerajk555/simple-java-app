# Simple Java Application

This is a simple Java application created for demonstrating Jenkins pipeline with declarative syntax.

## Features

- Maven-based Java 17 project
- JUnit 5 unit tests
- Jenkins pipeline with declarative syntax
- Automatic build, test, and package stages

## Building Locally

```bash
# Run tests
mvn clean test

# Build and package
mvn clean package

# Run the application
java -jar target/simple-java-app-1.0-SNAPSHOT.jar
```

## Jenkins Pipeline

The repository includes a `Jenkinsfile` with the following stages:

1. **Checkout**: Clone the source code
2. **Build**: Compile the Java application
3. **Test**: Run unit tests with JUnit
4. **Package**: Create JAR file
5. **Archive**: Store build artifacts

## Requirements

- Java 17 or higher
- Maven 3.6+
- Jenkins with Pipeline plugin

For detailed setup instructions, refer to the exercise documentation.