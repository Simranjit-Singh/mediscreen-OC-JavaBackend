FROM bellsoft/liberica-openjdk-alpine:latest
ADD target/report-service.jar report-service.jar
EXPOSE 8073
ENTRYPOINT ["java","-jar","report-service.jar"]