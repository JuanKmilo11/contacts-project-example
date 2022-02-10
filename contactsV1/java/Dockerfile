FROM openjdk:11
ARG JAR_FILE
ADD ${JAR_FILE} app.jar
VOLUME /tmp
EXPOSE 8080
ENTRYPOINT [ "sh", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./uradom -jar /app.jar" ]