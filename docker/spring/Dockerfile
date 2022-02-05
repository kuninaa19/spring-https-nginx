FROM openjdk:11
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=koboot-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} koboot.jar
ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","/koboot.jar"]