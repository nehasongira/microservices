FROM openjdk:11
WORKDIR usr/src
ADD ./target/zuulserver-0.0.1-SNAPSHOT.jar /zuulserver/src/zuulserver-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/zuulserver/src/zuulserver-0.0.1-SNAPSHOT.jar"]


