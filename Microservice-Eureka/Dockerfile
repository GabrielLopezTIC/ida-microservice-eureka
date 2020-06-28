FROM openjdk:8
VOLUME \tmp
EXPOSE 8761
ADD ./target/Microservice-Eureka-0.0.1-SNAPSHOT.jar Microservice-Eureka.jar
ENTRYPOINT ["java","-jar","/Microservice-Eureka.jar"]