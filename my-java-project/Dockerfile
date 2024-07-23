FROM openjdk:11-jre-slim
COPY target/my-java-project-1.0-SNAPSHOT.jar /usr/app/
WORKDIR /usr/app
ENTRYPOINT ["java", "-jar", "my-java-project-1.0-SNAPSHOT.jar"]

