FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
COPY index.html	index.html
ENTRYPOINT ["index.html","2223"]
ENTRYPOINT ["java","-jar","/app.jar","2223"]
