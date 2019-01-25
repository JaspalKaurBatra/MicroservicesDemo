FROM openjdk:11.0-jdk
ADD ./target/zuul-service-0.0.1-SNAPSHOT.jar /microservices/demo/zuul-service-0.0.1-SNAPSHOT.jar
WORKDIR microservices/demo
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "zuul-service-0.0.1-SNAPSHOT.jar"]
