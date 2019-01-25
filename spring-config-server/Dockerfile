FROM openjdk:11.0-jdk
ADD ./target/spring-config-server-0.0.1-SNAPSHOT.jar /microservices/demo/spring-config-server-0.0.1-SNAPSHOT.jar
WORKDIR microservices/demo
EXPOSE 8888
ENTRYPOINT ["java", "-jar", "spring-config-server-0.0.1-SNAPSHOT.jar"]
