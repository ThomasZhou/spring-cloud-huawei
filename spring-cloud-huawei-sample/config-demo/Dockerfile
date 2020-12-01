FROM openjdk:8u252-jre-slim

WORKDIR /app/
ARG JAR_FILE
ADD ${JAR_FILE} /app.jar

EXPOSE 8080
ENTRYPOINT ["/usr/local/openjdk-8/bin/java", "-jar", "/app.jar"]
