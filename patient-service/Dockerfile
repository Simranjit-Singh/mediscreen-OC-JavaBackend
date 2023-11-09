FROM bellsoft/liberica-openjdk-alpine:latest
ADD target/patient-service.jar patient-service.jar
EXPOSE 8071
ENTRYPOINT ["java","-jar","patient-service.jar"]