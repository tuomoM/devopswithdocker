FROM openjdk:latest

WORKDIR /app/
RUN yum install -y git
RUN git clone https://github.com/docker-hy/spring-example-project.git .
RUN ./mvnw package

ENTRYPOINT java -jar ./target/docker-example-1.1.3.jar




