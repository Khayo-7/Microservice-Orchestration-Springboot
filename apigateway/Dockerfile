FROM openjdk:11-jdk-slim
# FROM openjdk:11-jdk-alpine
# FROM openjdk:11

VOLUME /tmp

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} apigateway.jar

ENTRYPOINT ["java", "-jar", "/apigateway.jar"]

EXPOSE 9090