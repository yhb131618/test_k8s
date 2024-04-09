# Dockerfile for Spring Boot API

# Base image
FROM openjdk:latest

# Set working directory
WORKDIR /app

# Copy jar file
COPY target/myapp.jar myapp.jar

# Expose port
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "myapp.jar"]
