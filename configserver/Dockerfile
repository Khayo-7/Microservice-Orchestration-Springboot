FROM openjdk:11-jdk-slim
# FROM openjdk:11-jdk-alpine
# FROM openjdk:11

VOLUME /tmp

# ARG JAR_FILE=target/configserver-0.0.1-SNAPSHOT.jar
ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} configserver.jar

ENTRYPOINT ["java", "-jar", "/configserver.jar"]

EXPOSE 9296