FROM openjdk:8-alpine
USER root
COPY target/FinaOps-0.0.1-SNAPSHOT.jar /deployments/FinaOps-0.0.1-SNAPSHOT.jar 
RUN chmod 777 /deployments/FinaOps.jar
ENTRYPOINT ["java", "-jar", "/deployments/FinaOps-0.0.1-SNAPSHOT.jar"]
EXPOSE 8080
