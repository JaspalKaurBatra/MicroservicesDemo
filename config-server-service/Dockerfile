FROM openjdk:11.0-jdk
ADD ./target/config-server-service-0.0.1-SNAPSHOT.jar /microservices/demo/config-server-service-0.0.1-SNAPSHOT.jar
WORKDIR microservices/demo
EXPOSE 8888
ENTRYPOINT ["java", "-jar", "config-server-service-0.0.1-SNAPSHOT.jar"]
