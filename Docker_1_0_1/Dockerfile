FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} user-manag.jar
ENTRYPOINT ["java","-jar","/user-manag.jar"]