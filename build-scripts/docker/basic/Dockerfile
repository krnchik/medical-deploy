FROM openjdk:11

# Set default timezone
ENV TZ=Europe/Moscow

ARG JAR_FILE
ADD ${JAR_FILE} /opt/app.jar

ENTRYPOINT ["java", "-jar", "/opt/app.jar"]

