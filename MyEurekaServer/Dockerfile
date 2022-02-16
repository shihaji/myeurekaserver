FROM openjdk:8
ADD target/myeurekaserver.jar myeurekaserver.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","myeurekaserver.jar"]