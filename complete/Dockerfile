# Use OpenJDK 17 slim image (valid tag)
FROM openjdk:17-slim

# Set working directory
WORKDIR /app

# Copy the jar from target
COPY target/spring-boot-complete-0.0.1-SNAPSHOT.jar app.jar

# Expose port 9090 (since 8080 is used by Jenkins)
EXPOSE 9090

# Set Spring Boot to run on port 9090
ENV SERVER_PORT=9090

# Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]
