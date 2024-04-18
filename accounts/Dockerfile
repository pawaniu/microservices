# Start with the base image containing Java runtime
FROM openjdk:17-jdk-slim

MAINTAINER pawaniu

COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]