FROM openjdk:11
WORKDIR usr/src
ADD ./target/configserver-0.0.1-SNAPSHOT.jar /configserver/src/configserver-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/configserver/src/configserver-0.0.1-SNAPSHOT.jar"]


