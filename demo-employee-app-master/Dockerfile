FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} springWeb.jar
 ENTRYPOINT ["java","-jar","/springWeb.jar"]