FROM openjdk:17-alpine
VOLUME /main-app
ADD target/springassignment.jar springassignment.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar","/springassignment.jar"]