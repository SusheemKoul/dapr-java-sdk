FROM openjdk:11
COPY /target /target
ENTRYPOINT ["java", "-jar", "/target/dapr-java-sdk-examples-exec.jar", "io.dapr.examples.invoke.http.DemoService", "-p", "3000"]