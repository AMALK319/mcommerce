FROM openjdk:8
ADD target/*.jar clientui.jar
EXPOSE 9001
ENTRYPOINT ["java", "-jar", "clientui.jar"]
