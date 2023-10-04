FROM openjdk:22-jdk-slim
ADD ./target/*.jar /*.jar
CMD ["nohup", "java", "-jar", "-Dspring.profiles.active='mysql'", "*.jar"]
