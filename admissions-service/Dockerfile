FROM openjdk:8-jdk-alpine
VOLUME /tmp
#EXPOSE 8090
COPY target/admissions-service-0.0.1-SNAPSHOT.jar /admissions-service.jar
ENTRYPOINT [ "sh", "-c", "java -jar /admissions-service.jar"]