# 1. Base image
FROM eclipse-temurin:17-jre

# 2. Working directory
WORKDIR /app

# 3. Copy jar
COPY target/spring-boot-complete-0.0.1-SNAPSHOT.jar app.jar

# 4. Expose port
EXPOSE 8080

# 5. Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]
