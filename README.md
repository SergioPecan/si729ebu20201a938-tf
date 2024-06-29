# si729ebu20201a938 [Enterprise] Platform

## Summary
si729ebu20201a938 [Enterprise] Platform, illustrating development with Java, Spring Boot Framework, and Spring Data JPA on MySQL Database. It also illustrates open-api documentation configuration and integration with Swagger UI.

## Features
- RESTful API
- OpenAPI Documentation
- Swagger UI
- Spring Boot Framework
- Spring Data JPA
- Validation
- MySQL Database
- Domain-Driven Design

## Bounded Contexts
This version of si729ebu20201a938 [Enterprise] Platform is divided into two bounded contexts: Profiles, and Learning.

### [feature exam] Context

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.3.1/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.3.1/maven-plugin/reference/html/#build-image)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the
parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

