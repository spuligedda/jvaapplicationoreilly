FROM openjdk:11

COPY build/libs/hello-world-java-0.0.1-SNAPSHOT.jar /opt/myapp/

WORKDIR /opt/myapp/

ENTRYPOINT ["java", "-jar", "/opt/myapp/hello-world-java-0.0.1-SNAPSHOT.jar"]

EXPOSE 8080