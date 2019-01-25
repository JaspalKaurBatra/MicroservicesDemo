FROM openjdk:11.0-jdk
ADD ./target/eureka-service-0.0.1-SNAPSHOT.jar /microservices/demo/eureka-service-0.0.1-SNAPSHOT.jar
WORKDIR microservices/demo
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "eureka-service-0.0.1-SNAPSHOT.jar"]
