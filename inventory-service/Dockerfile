FROM openjdk:21-jdk

COPY target/inventory-service-0.0.1-SNAPSHOT.jar inventory-service.jar

EXPOSE 8082

ENTRYPOINT ["java","-jar","inventory-service.jar"]