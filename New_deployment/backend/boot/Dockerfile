# Use an official OpenJDK runtime as a base image
FROM openjdk:17

WORKDIR /usr/src/Elearning

COPY . /usr/src/Elearning/
# Set the entry point to run the JAR file
ENTRYPOINT ["java", "-jar", "ELearningUserService-0.0.1-SNAPSHOT.jar"]
