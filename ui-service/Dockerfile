FROM bellsoft/liberica-openjdk-alpine:latest
ADD target/ui-service.jar ui-service.jar
EXPOSE 8070
ENTRYPOINT ["java","-jar","ui-service.jar"]