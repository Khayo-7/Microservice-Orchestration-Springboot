FROM openjdk:11-jdk-slim
# FROM openjdk:11-jdk-alpine
# FROM openjdk:11

VOLUME /tmp

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} paymentservice.jar

ENTRYPOINT ["java", "-jar", "/paymentservice.jar"]

EXPOSE 8083