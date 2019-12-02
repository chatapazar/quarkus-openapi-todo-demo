# JAX-RS/RESTEasy server with OpenAPI

## Overview
This server was generated by the [OpenAPI Generator](https://openapi-generator.tech) project. By using an
[OpenAPI-Spec](https://openapis.org), you can easily generate a server stub.

This is an example of building a OpenAPI-enabled JAX-RS server.
This example uses the [JAX-RS](https://jax-rs-spec.java.net/) framework.
RESTEasy is used as JAX-RS implementation library and is defined as dependency.

To run the server **WITH** the UI, please execute the following:

```bash
mvn clean compile quarkus:dev
```

To run the server **WITHOUT** the UI, please execute the following:

```bash
./mvnw clean compile quarkus:dev -Pquarkus-test-only
```