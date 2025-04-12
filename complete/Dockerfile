# Use an official OpenJDK image as the base
FROM openjdk:17-jdk-alpine

# Set the working directory
WORKDIR /app

# Add the jar file
COPY target/todo-api-0.0.1-SNAPSHOT.jar app.jar

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
