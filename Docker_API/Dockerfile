FROM openjdk:17-alpine
WORKDIR /opt
ENV PORT=8090
COPY target/*.jar /opt/app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
