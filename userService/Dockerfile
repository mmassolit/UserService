FROM openjdk:11
WORKDIR /Users/max_slob/git/UserService
COPY target/userService-0.0.1-SNAPSHOT.jar service.jar
EXPOSE 8082
CMD ["java", "-jar", "service.jar"]