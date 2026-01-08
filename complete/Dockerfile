# Use Java 17 image
FROM openjdk:17-jdk-slim

# Set workdir
WORKDIR /app

# Copy the jar built by Maven
COPY target/spring-boot-complete-0.0.1-SNAPSHOT.jar app.jar

# Expose port
EXPOSE 8080

# Run the app
ENTRYPOINT ["java","-jar","app.jar"]
