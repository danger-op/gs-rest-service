# Use an official OpenJDK 17 image
FROM openjdk:17-jdk-alpine

# Set the working directory
WORKDIR /app

# Add the jar file
COPY target/rest-service-complete-0.0.1.jar app.jar

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
