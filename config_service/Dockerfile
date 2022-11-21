FROM openjdk:8-jdk-alpine
EXPOSE 8001
COPY build/libs/config_service-1.0-SNAPSHOT.jar .
ENTRYPOINT ["java", "-jar", "config_service-1.0-SNAPSHOT.jar"]