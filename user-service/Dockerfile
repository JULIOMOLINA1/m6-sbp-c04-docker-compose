FROM eclipse-temurin:17-jre

WORKDIR /app

COPY target/*.jar /app/user-service.jar

EXPOSE 8081

CMD ["java", "-jar", "/app/user-service.jar"]
