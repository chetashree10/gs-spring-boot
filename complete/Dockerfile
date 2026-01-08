# Use OpenJDK 17 slim image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy the jar from target
COPY target/spring-boot-complete-0.0.1-SNAPSHOT.jar app.jar

# Expose port 9090 instead of 8080
EXPOSE 9090

# Set environment variable for Spring Boot to run on 9090
ENV SERVER_PORT=9090

# Run the jar
ENTRYPOINT ["java","-jar","app.jar"]
