FROM openjdk:17.0.2-slim-buster

COPY target/*.jar ./app.jar

EXPOSE 8000 

CMD [ "java", "-jar","./app.jar" ]
