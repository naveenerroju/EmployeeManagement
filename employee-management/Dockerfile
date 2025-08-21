FROM openjdk:23-jdk-slim

WORKDIR /app

# Copy the JAR file
COPY target/*.jar app.jar

# Expose port 8080 (as defined in docker properties)
EXPOSE 8080

# Run with docker profile
ENTRYPOINT ["java", "-jar", "app.jar"]