# RESTful Microservice Quickstart

To package the service, run `mvn clean package` to create an executable jar file.
To launch the service locally, run `java -jar target/<name-of-jar>.jar`.

For more details, please read
[Building a RESTful Web Service](http://spring.io/guides/gs/rest-service/).

# Development

## Spring Framework

### [Spring Actuator](https://spring.io/guides/gs/actuator-service/)

Spring Actuator adds additional production-grade features such as determining if the service is up
and switching ports via `application.properties`.

Navigate to `/actuator/health` to run the health check.
