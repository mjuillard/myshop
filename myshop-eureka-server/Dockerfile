FROM openjdk:8-jdk-alpine

EXPOSE 8761
COPY ./target/myshop-eureka-server-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/app.jar"]