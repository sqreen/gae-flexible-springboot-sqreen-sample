FROM openjdk:11-jre-slim

COPY helloworld-*.jar /app.jar
COPY sqreen.jar /sqreen.jar

CMD ["java", "-javaagent:sqreen.jar", "-Dsqreen.log_level=INFO", "-jar", "/app.jar"]
