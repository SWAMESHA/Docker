#define base docker image
FROM openjdk:8
ADD target/spring-docker-a.jar spring-docker-a.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/spring-docker-a.jar"]