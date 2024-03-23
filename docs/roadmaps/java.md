# :fontawesome-brands-java: Java Developer Roadmap

!!! info "Legend"
    :green_heart: Must Know
    :material-emoticon-excited-outline:{ .good_to_know } Good to Know
    :material-lightning-bolt:{ .alternative } Alternative
    :no_entry: Not Recommended

## Version Control

- :green_heart: [Git](https://git-scm.com/)
- :green_heart: [GitHub](https://github.com/)
- :material-lightning-bolt:{ .alternative } [GitLab](https://gitlab.com/)
- :no_entry: Mercurial
- :no_entry: SVN/Subversion

## Java

- :green_heart: Java 21
    - **Basic Syntax**: Variables, control flow (if, for, while), methods, classes, and interfaces.
    - **Advanced Features**: Generics, lambda expressions, streams, functional interfaces, concurrency model, CompletableFuture for asynchronous programming.
    - **Error Handling**: Exception handling using try, catch, finally, and throws clauses.
    - **Data Types**: Understanding primitive types vs. reference types, optionals, and records.
    - Virtual threads, Garbage collection and Java tuning for containerization
- :green_heart: [Maven](https://maven.apache.org/) / [Gradle](https://gradle.org/)
- :material-emoticon-excited-outline:{ .good_to_know } [Spring Framework](https://spring.io/)
    - Spring Boot
    - Spring MVC
    - Spring Data JPA
    - Spring Security

## Architecture

- :green_heart: [SOLID](../architecture/solid.md) Principles
- :green_heart: MVC - Model View Controller
- :green_heart: [Microservices with Spring](https://spring.io/microservices)
- :green_heart: [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- :green_heart: [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
- :green_heart: [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- :material-emoticon-excited-outline:{ .good_to_know } Clean (Hexagonal) Architecture
- :material-emoticon-excited-outline:{ .good_to_know } Domain-Driven Design (DDD)

## Web Development

- :green_heart: Spring MVC
- :green_heart: [Spring WebFlux](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html) for reactive programming
- Authentication
    - :green_heart: JWT
    - :green_heart: OAuth2
    - :green_heart: Basic Auth
    - :material-emoticon-excited-outline:{ .good_to_know } OpenID Connect
- :green_heart: Authorization with Spring Security
- :green_heart: Dependency Injection with Spring Framework

## RDBMS Databases

- :green_heart: RDBMS Fundamentals
- :green_heart: SQL Syntax
- :no_entry: Stored procedures
- :no_entry: Triggers
- Vendor specific databases
    - :green_heart: PostgreSQL
    - :green_heart: MySQL/MariaDB
    - :no_entry: SQL Server
    - :no_entry: Oracle

## APIs

- :green_heart: REST
    - Spring Web
- :material-emoticon-excited-outline:{ .good_to_know } GraphQL
    - [Spring for GraphQL](https://spring.io/projects/spring-graphql)
- :material-emoticon-excited-outline:{ .good_to_know } gRPC
    - [gRPC Spring Boot Starter](https://yidongnan.github.io/grpc-spring-boot-starter/en/)

## ORMs

- :green_heart: [Hibernate](https://hibernate.org/)
- :green_heart: [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- :material-lightning-bolt:{ .alternative } JOOQ
- :material-lightning-bolt:{ .alternative } Jooq

## Dependency Injection

- :green_heart: Spring Framework DI

## NoSQL Databases

- :green_heart: Redis
- :green_heart: ElasticSearch
- :material-emoticon-excited-outline:{ .good_to_know } Cloud proprietary
    - AWS DynamoDB
    - Azure Cosmos DB
- :material-emoticon-excited-outline:{ .good_to_know } Apache Cassandra
- :material-lightning-bolt:{ .alternative } MongoDB

## Caching

- :green_heart: Redis
- :material-lightning-bolt:{ .alternative } [EhCache](https://www.ehcache.org/)

## Logging

- :green_heart: [SLF4J](http://www.slf4j.org/) with [Logback](http://logback.qos.ch/)
- :material-emoticon-excited-outline:{ .good_to_know } [Log4j2](https://logging.apache.org/log4j/2.x/)

## Messaging

- :green_heart: Apache Kafka
- :green_heart: RabbitMQ
- :material-lightning-bolt:{ .alternative } ActiveMQ

## Security

- :green_heart: Secure coding practices
- :green_heart: Data protection

## Front-End Technologies

- :material-emoticon-excited-outline:{ .good_to_know } Responsive Design: CSS, Bootstrap, Tailwind CSS
- :material-emoticon-excited-outline:{ .good_to_know } SPA frameworks: Angular, React, Vue.js with Java backends

## Unit Testing

### Frameworks

- :green_heart: [JUnit](https://junit.org/junit5/)
- :material-emoticon-excited-outline:{ .good_to_know } [TestNG](https://testng.org/doc/)

### Mocking

- :green_heart: [Mockito](https://site.mockito.org/)
- :green_heart: [EasyMock](https://easymock.org/)

### Assertions

- :green_heart: [AssertJ](https://assertj.github.io/doc/)

### Test Data

- :green_heart: [JUnit QuickCheck](https://pholser.github.io/junit-quickcheck/site/0.9/)

## Integration Testing

- :green_heart: [Spring Test](https://docs.spring.io/spring-framework/docs/current/reference/html/testing.html)

## Performance Testing

- :green_heart: [Gatling](https://gatling.io/)
- :material-lightning-bolt:{ .alternative } [Apache JMeter](https://jmeter.apache.org/)

## Containers

- :green_heart: Docker
- :material-lightning-bolt:{ .alternative } [Podman](https://podman.io/)
- :material-lightning-bolt:{ .alternative } [Rancher](https://rancherdesktop.io/)
- Orchestration
    - :green_heart: [Docker Compose](https://docs.docker.com/compose/)
    - :green_heart: Kubernetes
- Tooling
    - :green_heart: Minikube
    - :green_heart: [K9s](https://k9scli.io/)
    - :material-lightning-bolt:{ .alternative } [Lens](https://k8slens.dev/)
    - :material-lightning-bolt:{ .alternative } [Skaffold](https://skaffold.dev/)

## Cloud

- Providers
    - :green_heart: AWS
    - :green_heart: Azure
- Serverless
    - :green_heart: AWS Lambda
    - :green_heart: Azure Functions
- Storage
    - :green_heart: AWS S3
    - :green_heart: Azure Blob Storage

## CI/CD (Continuous Integration & Deployment)

- :green_heart: GitHub Actions
- :material-emoticon-excited-outline:{ .good_to_know } TeamCity
- :material-emoticon-excited-outline:{ .good_to_know } Azure Pipelines
- :material-emoticon-excited-outline:{ .good_to_know } Jenkins
- :material-lightning-bolt:{ .alternative } Bamboo
- :material-lightning-bolt:{ .alternative } GitLab CI
- :material-lightning-bolt:{ .alternative } Octopus Deploy

## Java Libraries

- :green_heart: [Lombok](https://projectlombok.org/) for boilerplate code reduction
- :green_heart: [Guava](https://github.com/google/guava) for core libraries
- :green_heart: [Apache Commons](https://commons.apache.org/)

## DevOps

- Infrastructure as Code
    - :green_heart: [TerraForm](https://www.terraform.io/) Infrastructure automation to provision and manage resources in any cloud or data center
    - :material-lightning-bolt:{ .alternative } [Pulumi](https://www.pulumi.com/) Infrastructure as code in any programming language
    - :material-lightning-bolt:{ .alternative } Ansible
