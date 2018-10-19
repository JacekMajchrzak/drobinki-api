FROM openjdk:8-jre-alpine

MAINTAINER drobinki.pl <drobinki.pl@gmail.com>

ADD build/libs/discovery-service-0.0.1-SNAPSHOT.jar discovery-service.jar

ENTRYPOINT ["java", "-jar", "/discovery-service.jar"]

EXPOSE 8761