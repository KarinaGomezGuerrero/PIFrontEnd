FROM amazoncorretto:11-alpine-jdk
MAINTAINER KGG
COPY target/kgg-0.0.1-SNAPSHOT.jar  kgg-app.jar
ENTRYPOINT ["java","-jar","/kgg-app.jar"]