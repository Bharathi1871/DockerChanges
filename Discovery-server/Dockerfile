FROM openjdk:8-jdk-alpine
VOLUME /temp
##EXPOSE 8092
COPY /target/Discovery-server-0.0.1-SNAPSHOT.jar /Discovery-server.jar
ENTRYPOINT [ "sh", "-c", "java -jar /Discovery-server.jar"]