FROM openjdk:21-jdk-slim
WORKDIR /app
COPY target/ServiceDiscoveryRevshop-0.0.1-SNAPSHOT.jar serviceDiscoveryRevshop.jar
ENTRYPOINT ["java","-jar","serviceDiscoveryRevshop.jar"]