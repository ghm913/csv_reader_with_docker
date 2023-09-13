# base image
FROM eclipse-temurin:8-jdk

WORKDIR /app
# copy java project
COPY ./csv_reader_with_docker.jar /app/app.jar

# expose port 8080
EXPOSE 8080

# entry，start java project
ENTRYPOINT java -jar /app/app.jar