FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
RUN mkdir app
WORKDIR /app
COPY ${JAR_FILE} /app/app.jar
ENTRYPOINT ["java","-jar","app.jar"]