FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8091
COPY target/admissions-config-server-0.0.1-SNAPSHOT.jar /admissions-config-server.jar
ENTRYPOINT [ "sh", "-c", "java -jar /admissions-config-server"]