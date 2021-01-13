FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8093
COPY target/hr-service-0.0.1-SNAPSHOT.jar /hr-service.jar
ENTRYPOINT [ "sh", "-c", "java -jar /hr-service.jar"]