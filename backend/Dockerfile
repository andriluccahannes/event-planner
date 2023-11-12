FROM openjdk:21

WORKDIR /app

COPY . .

RUN  ./mvnw clean install -DskipTests

EXPOSE 8080

CMD ["java", "-jar", "target/event-planner-0.0.1-SNAPSHOT.jar"]