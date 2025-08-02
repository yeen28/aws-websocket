FROM amazoncorretto:17-alpine-jre
WORKDIR /app
COPY build/libs/*-SNAPSHOT.jar app.jar
EXPOSE 8081
ENTRYPOINT ["java", "-Xms512m", "-Xmx1024m", "-jar", "app.jar"]
