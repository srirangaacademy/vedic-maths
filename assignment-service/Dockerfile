FROM eclipse-temurin:21-jre AS runtime
WORKDIR /app
ARG JAR=target/*.jar
COPY ${JAR} app.jar
EXPOSE 8104
ENTRYPOINT ["java","-jar","/app/app.jar"]
