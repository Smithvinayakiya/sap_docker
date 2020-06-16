FROM openjdk:8-jdk-alpine
COPY ./target/*.jar app.jar
ENV KAFKA_BOOTSTRAP_SERVERS="localhost:9092"
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8092