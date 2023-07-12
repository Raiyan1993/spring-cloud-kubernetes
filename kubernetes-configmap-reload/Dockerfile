FROM openjdk:21-ea-27-jdk-slim
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java -jar app.jar --info
