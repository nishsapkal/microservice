FROM adoptopenjdk:11-jre-hotspot as builder
ARG JAR_FILE=rest-service-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
