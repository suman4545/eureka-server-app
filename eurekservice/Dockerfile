FROM java:8
EXPOSE 8761
ADD /target/eurekservice-0.0.1-SNAPSHOT.jar eureka-server-app.jar
ENTRYPOINT ["java","-jar","eureka-server-app.jar"]