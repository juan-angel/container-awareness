FROM maven:3.5.3-jdk-8-slim
COPY target/java8-0.0.1-SNAPSHOT.jar /app.jar
ENTRYPOINT [ "java", "-jar", "/app.jar" ]
