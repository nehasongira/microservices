FROM openjdk:11
WORKDIR usr/src
ADD ./target/eureka-server-0.0.1-SNAPSHOT.jar /eureka-server/src/eureka-server-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/eureka-server/src/eureka-server-0.0.1-SNAPSHOT.jar"]


