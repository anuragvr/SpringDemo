# SpringDemo

SpringDemo is a simple Spring Boot demo project that demonstrates common patterns and a starter template for building microservices and web applications with the Spring ecosystem.

## Features
- Spring Boot application structure
- Example REST endpoints
- Basic unit and integration test setup

## Prerequisites
- Java 11 or newer
- Maven 3.6+ (or Gradle if the project uses Gradle)

## Getting Started
1. Clone the repository:

   git clone https://github.com/anuragvr/SpringDemo.git
   cd SpringDemo

2. Build and run with Maven:

   mvn clean package
   mvn spring-boot:run

   Or run the built JAR:

   java -jar target/*.jar

3. The application will start on port 8080 by default. You can change this in `src/main/resources/application.properties` or `application.yml`.

## Running Tests

Run unit and integration tests with:

   mvn test

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## License

Specify a license for your project (e.g., MIT, Apache-2.0) in a LICENSE file.
