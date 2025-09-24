FROM openjdk:11-jre
ENV SPRING_PROFILES_ACTIVE docker
COPY ./target/*.jar /app.jar
EXPOSE 7979
ENTRYPOINT ["java", "-jar","/app.jar"]