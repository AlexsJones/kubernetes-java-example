# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine
# copy fat WAR
COPY build/libs/webapp-0.1.0.jar /webapp-0.1.0.jar
# runs application
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/webapp-0.1.0.jar"]