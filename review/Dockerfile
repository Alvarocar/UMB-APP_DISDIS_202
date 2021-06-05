FROM openjdk:15.0.2
EXPOSE 8080
COPY target/review-0.0.1-SNAPSHOT.jar .
ENTRYPOINT ["java","-Dspring.profiles.active=container", "-jar", "review-0.0.1-SNAPSHOT.jar"]
