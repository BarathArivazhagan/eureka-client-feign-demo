FROM openjdk:8-jdk-alpine as final
MAINTAINER BARATH
ADD target/eureka-client-app2-*.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]