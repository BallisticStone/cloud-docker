FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD hi-service-0.0.1-SNAPSHOT.jar hi-service.jar
ENTRYPOINT ["java","-jar","/hi-service.jar"]
EXPOSE 8763

