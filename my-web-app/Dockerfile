From maven:3.8.6-eclipse-termurin-17
WORKDIR /app
COPY . /app 
RUN mvn clean package
EXPOSE 8080
CMD ["java", "-jar", "target/my-web-app-1.0-SNAPSHOT.jar"]