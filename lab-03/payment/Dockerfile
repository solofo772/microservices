FROM openjdk:17-jdk-slim 
COPY target/exec/payment-1.0.0-SNAPSHOT-exec.jar /usr/local/lib/payment.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/usr/local/lib/payment.jar"]
