FROM java:openjdk-8-jre
VOLUME /tmp
ADD hello-world-app-1-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]