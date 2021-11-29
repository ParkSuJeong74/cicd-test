FROM openjdk:11-jdk-slim 
ARG JAR_FILE=build/libs/*.jar 
ADD ${JAR_FILE} cicd-test.jar 
ENTRYPOINT ["java", "-jar", "cicd-test.jar"]