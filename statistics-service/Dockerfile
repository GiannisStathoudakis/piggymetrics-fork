FROM eclipse-temurin:8-jre
LABEL maintainer="sqshq@sqshq.com"

ADD ./target/statistics-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/statistics-service.jar"]
EXPOSE 7000