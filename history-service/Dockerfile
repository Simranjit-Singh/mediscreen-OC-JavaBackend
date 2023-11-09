FROM bellsoft/liberica-openjdk-alpine:latest
ADD target/history-service.jar history-service.jar
EXPOSE 8072
ENTRYPOINT ["java","-jar","history-service.jar"]