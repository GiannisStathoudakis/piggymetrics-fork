FROM eclipse-temurin:8-jre
LABEL maintainer="sqshq@sqshq.com"

ADD ./target/notification-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/notification-service.jar"]
EXPOSE 8000