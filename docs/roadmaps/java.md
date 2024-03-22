# :fontawesome-brands-java: Java Developer Roadmap
## Legend
- 🟢 Must Know
- 🔵 Good to Know
- 🟣 Alternative
- ⛔ Not Recommended

## Required Developer Skills
### Version Control
- 🟢 [Git](https://git-scm.com/)
- 🟢 [GitHub](https://github.com/)
- 🟣 [GitLab](https://gitlab.com/)
- ⛔ Mercurial
- ⛔ SVN/Subversion
### Java
- 🟢 Java 17
    - **Basic Syntax**: Variables, control flow (if, for, while), methods, classes, and interfaces.
    - **Advanced Features**: Generics, lambda expressions, streams, functional interfaces, concurrency model, CompletableFuture for asynchronous programming.
    - **Error Handling**: Exception handling using try, catch, finally, and throws clauses.
    - **Data Types**: Understanding primitive types vs. reference types, optionals, and records.
- 🟢 [Maven](https://maven.apache.org/) / [Gradle](https://gradle.org/)
- 🔵 [Spring Framework](https://spring.io/)
    - Spring Boot
    - Spring MVC
    - Spring Data JPA
    - Spring Security
### Architecture
- 🟢 SOLID Principles
- 🟢 MVC - Model View Controller
- 🟢 [Microservices with Spring](https://spring.io/microservices)
- 🟢 [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- 🟢 [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
- 🟢 [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- 🔵 Clean (Hexagonal) Architecture
- 🔵 Domain-Driven Design (DDD)
### Web Development
- 🟢 Spring MVC
- 🟢 [Spring WebFlux](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html) for reactive programming
- Authentication
    - 🟢 JWT
    - 🟢 OAuth2
    - 🟢 Basic Auth
    - 🔵 OpenID Connect
- 🟢 Authorization with Spring Security
- 🟢 Dependency Injection with Spring Framework
### RDBMS Databases
- 🟢 RDBMS Fundamentals
- 🟢 SQL Syntax
- ⛔ Stored procedures
- ⛔ Triggers
- Vendor specific databases
    - 🟢 PostgreSQL
    - 🟢 MySQL/MariaDB
    - ⛔ SQL Server
    - ⛔ Oracle
### APIs
- 🟢 REST
    - Spring Web
- 🔵 GraphQL
    - [Spring for GraphQL](https://spring.io/projects/spring-graphql)
- 🔵 gRPC
    - [gRPC Spring Boot Starter](https://yidongnan.github.io/grpc-spring-boot-starter/en/)
### ORMs
- 🟢 [Hibernate](https://hibernate.org/)
- 🟢 [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- 🟣 Jooq
### Dependency Injection
- 🟢 Spring Framework DI
### NoSQL Databases
- 🟢 Redis
- 🟢 ElasticSearch
- 🔵 Cloud proprietary
    - AWS DynamoDB
    - Azure Cosmos DB
- 🔵 Apache Cassandra
- 🟣 MongoDB
### Caching
- 🟢 Redis
- 🟣 [EhCache](https://www.ehcache.org/)
### Logging
- 🟢 [SLF4J](http://www.slf4j.org/) with [Logback](http://logback.qos.ch/)
- 🔵 [Log4j2](https://logging.apache.org/log4j/2.x/)
### Messaging
- 🟢 Apache Kafka
- 🟢 RabbitMQ
- 🟣 ActiveMQ
### Security
- 🟢 Secure coding practices
- 🟢 Data protection
### Front-End Technologies
- 🔵 Responsive Design: CSS, Bootstrap, Tailwind CSS
- 🔵 SPA frameworks: Angular, React, Vue.js with Java backends
### Unit Testing
#### Frameworks
- 🟢 [JUnit](https://junit.org/junit5/)
- 🔵 [TestNG](https://testng.org/doc/)
#### Mocking
- 🟢 [Mockito](https://site.mockito.org/)
- 🟢 [EasyMock](https://easymock.org/)
#### Assertions
- 🟢 [AssertJ](https://assertj.github.io/doc/)
#### Test Data
- 🟢 [JUnit QuickCheck](https://pholser.github.io/junit-quickcheck/site/0.9/)
### Integration Testing
- 🟢 [Spring Test](https://docs.spring.io/spring-framework/docs/current/reference/html/testing.html)
### Performance Testing
- 🟢 [Gatling](https://gatling.io/)
- 🟣 [Apache JMeter](https://jmeter.apache.org/)
### Containers
- 🟢 Docker
- 🟣 [Podman](https://podman.io/)
- 🟣 [Rancher](https://rancherdesktop.io/)
- Orchestration
    - 🟢 [Docker Compose](https://docs.docker.com/compose/)
    - 🟢 Kubernetes
- Tooling
    - 🟢 Minikube
    - 🟢 [K9s](https://k9scli.io/)
    - 🟣 [Lens](https://k8slens.dev/)
    - 🟣 [Skaffold](https://skaffold.dev/)
### Cloud
- Providers
    - 🟢 AWS
    - 🟢 Azure
- Serverless
    - 🟢 AWS Lambda
    - 🟢 Azure Functions
- Storage
    - 🟢 AWS S3
    - 🟢 Azure Blob Storage
### CI/CD (Continuous Integration & Deployment)
- 🟢 GitHub Actions
- 🔵 TeamCity
- 🔵 Azure Pipelines
- 🔵 Jenkins
- 🟣 Bamboo
- 🟣 GitLab CI
- 🟣 Octopus Deploy
### Java Libraries
- 🟢 [Lombok](https://projectlombok.org/) for boilerplate code reduction
- 🟢 [Guava](https://github.com/google/guava) for core libraries
- 🟢 [Apache Commons](https://commons.apache.org/)
### DevOps
- Infrastructure as Code
    - 🟢 [TerraForm](https://www.terraform.io/) Infrastructure automation to provision and manage resources in any cloud or data center
    - 🟣 [Pulumi](https://www.pulumi.com/) Infrastructure as code in any programming language
    - 🟣 Ansible