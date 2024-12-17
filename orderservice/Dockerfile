FROM openjdk:11-jdk-slim
# FROM openjdk:11-jdk-alpine
# FROM openjdk:11

VOLUME /tmp

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} orderservice.jar

ENTRYPOINT ["java", "-jar", "/orderservice.jar"]

EXPOSE 8082