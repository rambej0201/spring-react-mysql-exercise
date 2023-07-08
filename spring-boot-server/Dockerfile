FROM openjdk:19-alpine@sha256:5bf18c827959c2d7b56b27328547faeefba886f23be35c0fe2093a5353135d99
ARG JAR_FILE=target/spring-boot-data-jpa-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} spring-boot-data-jpa.jar
ENTRYPOINT ["java","-jar","/spring-boot-data-jpa.jar"]
EXPOSE 8080