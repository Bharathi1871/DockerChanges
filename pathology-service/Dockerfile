FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8094
COPY target/pathology-service-0.0.1-SNAPSHOT.jar /pathology-service.jar
ENTRYPOINT [ "sh", "-c", "java -jar /pathology-service.jar"]