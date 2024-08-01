# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the jar file into the container at /app
COPY DoctorInfo.jar .

# Run the jar file
ENTRYPOINT ["java", "-jar", "DoctorInfo.jar"]

EXPOSE 9090 9091
