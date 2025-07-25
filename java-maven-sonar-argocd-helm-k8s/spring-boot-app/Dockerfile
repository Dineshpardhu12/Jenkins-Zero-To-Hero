# Use Java 17 runtime instead of Java 11
FROM eclipse-temurin:17-jre-alpine

# Artifact path from Maven build
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]




