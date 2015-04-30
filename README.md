# Apache CXF REST Service with Spring Boot

Quick and dirty example how to serve REST service with Apache CXF running on Spring Boot.

## spring-boot-cxf-rest-example-api

RAML API description with JSON schema. JAX-RS interfaces are generated using [raml-jaxrs-maven-plugin](https://github.com/mulesoft/raml-for-jax-rs).

## spring-boot-cxf-rest-example-service

Implementation for the service

## spring-boot-cxf-rest-example-app

Spring Boot application.

Start the application:

	$ java -jar spring-boot-cxf-rest-example-app-1.0-SNAPSHOT.jar

Test it:

  $ curl "127.0.0.1:8080/example/hello"
	$ curl "127.0.0.1:8080/example/hello?greeting=Hey&name=dude"
