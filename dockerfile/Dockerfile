FROM openjdk:17-jdk-slim
WORKDIR /app
COPY ./target/my-shop-1.0.jar app.jar
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
