# :material-language-csharp: .NET Developer Roadmap

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

## CSharp

- :green_heart: [CSharp 12](https://learn.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-12)
    - **Basic Syntax**: Variables, control flow (if, for, while), methods, classes, and interfaces.
    - **Advanced Features**: Generics, delegates, events, LINQ, async/await.
    - **Error Handling**: Exception handling using try, catch, finally blocks.
    - **Data Types**: Understanding value types vs. reference types, nullable types, tuples, and records.
    - **Latest Enhancements**: Records, top-level statements, pattern matching enhancements.
- :green_heart: [.NET 8](https://learn.microsoft.com/en-us/dotnet/core/whats-new/dotnet-8/overview)
- :green_heart: [.NET CLI](https://learn.microsoft.com/en-us/dotnet/core/tools/)
- :material-emoticon-excited-outline:{ .good_to_know } [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-overview)
    - [Apir8](https://prom3theu5.github.io/aspirational-manifests/getting-started.html)

## Architecture

- :green_heart: [SOLID](https://learn.microsoft.com/en-us/archive/msdn-magazine/2014/may/csharp-best-practices-dangers-of-violating-solid-principles-in-csharp) Principles
- :green_heart: MVC - Model View Controller
- :green_heart: MVVM - Model View ViewModel
- :green_heart: [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- :green_heart: [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
- :green_heart: [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- :green_heart: Design Patterns (Gang of Four)
- :green_heart: Microservices Architecture: Patterns and Best Practices (e.g., CQRS, Event Sourcing)
- :material-emoticon-excited-outline:{ .good_to_know } [Clean](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#clean-architecture) (Onion) Architecture and Domain-Driven Design (DDD)
- :material-emoticon-excited-outline:{ .good_to_know } [Vertical](https://medium.com/@v.cheshmi/introduction-ae32b9f32ac5) [Slice Architecture](https://blog.ndepend.com/vertical-slice-architecture-in-asp-net-core/)

## ASP.NET Core

- :green_heart: [Web API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-8.0&tabs=visual-studio)
- :green_heart: [Minimal API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio)
- :green_heart: [Routing](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-8.0)
- :green_heart: [Middleware](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-8.0)
- :green_heart: [Filters](https://learn.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-8.0)
- :green_heart: [Configuration](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-8.0)
- Authentication
    - :green_heart: [JWT](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/jwt-authn?view=aspnetcore-8.0&tabs=windows)
    - :green_heart: [Basic Auth](https://learn.microsoft.com/en-us/aspnet/web-api/overview/security/basic-authentication)
    - :green_heart: Token Auth
    - :green_heart: OAuth
    - :green_heart: Cookies
    - :material-emoticon-excited-outline:{ .good_to_know } OpenID
    - :material-emoticon-excited-outline:{ .good_to_know } SAML
- :material-emoticon-excited-outline:{ .good_to_know } IdentityServer/Duende IdentityServer for implementing these protocols
- :green_heart: Authorization
- :green_heart: Dependency Injection
- :material-emoticon-excited-outline:{ .good_to_know } Integrating with modern JavaScript frameworks (React, Angular, Vue)

## RDBMS Databases

- :green_heart: RDBMS Fundementals
- :green_heart: SQL Syntax
- :no_entry: Stored procedures
- :no_entry: Triggers
- Vendor specific databases
    - :green_heart: PostgreSQL
    - :green_heart: SQL Server
    - :material-emoticon-excited-outline:{ .good_to_know } MySQL/MariaDB
    - :no_entry: Oracle

## APIs

- :green_heart: REST
    - :green_heart: Minimal API
    - :green_heart: Web API
    - :material-lightning-bolt:{ .alternative } [FastEndpoints](https://fast-endpoints.com/)
- :material-emoticon-excited-outline:{ .good_to_know } GraphQL
    - :green_heart: [HotChocolate](https://chillicream.com/docs/hotchocolate/v13)
- :material-emoticon-excited-outline:{ .good_to_know } gRPC

## ORMs

- :green_heart: [Dapper](https://github.com/DapperLib/Dapper)
- :green_heart: Entity Framework Core
    - EF Basics
    - Code first
    - Migrations
    - Change tracker API
    - Loading modes
    - Interceptors
- :material-lightning-bolt:{ .alternative } [RepoDB](https://repodb.net/)
- :no_entry: NHibernate

## Dependency Injection

- :green_heart: Microsoft.Extensions.DependencyInjection
- :material-emoticon-excited-outline:{ .good_to_know } [Scrutor](https://github.com/khellang/Scrutor)

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
    - Stackexchange.Redis
- :green_heart: Output caching
- :no_entry: Response caching

## Logging

- :green_heart: Microsoft.Extensions.Logging
- :green_heart: Serilog
- :material-emoticon-excited-outline:{ .good_to_know } NLog
- :no_entry: Log4Net

## Messaging

- :green_heart: Azure Service Bus
- :green_heart: AWS SQS/SNS
- :green_heart: [MassTransit](https://masstransit.io/)
- :green_heart: RabbitMQ
- :material-lightning-bolt:{ .alternative } [Wolverine](https://wolverine.netlify.app/)
- :no_entry: NServiceBus

## Security

- :green_heart: Secure coding practices
- :green_heart: Data protection
- :green_heart: ASP.NET Core security features

## Front-End Technologies

- :material-emoticon-excited-outline:{ .good_to_know } Responsive Design: CSS, Bootstrap, Tailwind CSS
- :material-emoticon-excited-outline:{ .good_to_know } SPA frameworks: Angular, React, Vue.js with .NET backends

## Unit Testing

### Frameworks

- :green_heart: [NUnit](https://nunit.org/)
- :green_heart: [xUnit](https://xunit.net/)
- :no_entry: MsTest

### Mocking

- :green_heart: [NSubstitute](https://nsubstitute.github.io/)
- :green_heart: [Moq](https://github.com/devlooped/moq)
- :material-lightning-bolt:{ .alternative } [FakeItEasy](https://fakeiteasy.github.io/)

### Assertions

- :green_heart: [FluentAssertions](https://fluentassertions.com/)
- :material-lightning-bolt:{ .alternative } [Shouldly](https://docs.shouldly.org/)

### Test Data

- :green_heart: [Bogus](https://github.com/bchavez/Bogus)
- :green_heart: [AutoFixture](https://github.com/AutoFixture/AutoFixture)

## Integration Testing

- :green_heart: WebApplicationFactory
    - TestContainers
    - Respawn
- :material-lightning-bolt:{ .alternative } Postman
- :material-lightning-bolt:{ .alternative } TestServer

## Snapshot Testing

- :material-emoticon-excited-outline:{ .good_to_know } [Verify](https://github.com/VerifyTests/Verify)

## E2E Testing

- :material-emoticon-excited-outline:{ .good_to_know } [Playwright](https://playwright.dev/)
- :no_entry: Selenium

## Performance Testing

- :green_heart: [K6](https://k6.io/)
- :material-lightning-bolt:{ .alternative } [NBomber](https://nbomber.com/)
- :material-lightning-bolt:{ .alternative } [JMeter](https://jmeter.apache.org/)

## Streaming

- :material-emoticon-excited-outline:{ .good_to_know } Apache Kafka
- :material-lightning-bolt:{ .alternative } AWS Kinesis
- :material-lightning-bolt:{ .alternative } Azure Event Hubs

## Real-Time Communication

- :material-emoticon-excited-outline:{ .good_to_know } SignalR
- :material-emoticon-excited-outline:{ .good_to_know } WebSockets

## API Documentation

- :green_heart: OpenAPI
- :material-emoticon-excited-outline:{ .good_to_know } AsyncAPI

## API Libraries

- :green_heart: [Refit](https://reactiveui.github.io/refit/)
- :green_heart: [RestSharp](https://restsharp.dev/)
- :material-lightning-bolt:{ .alternative } [Flurl](https://flurl.dev/)

## Task Scheduling

- :green_heart: BackgroundService
- :green_heart: PeriodicTimer
- :material-emoticon-excited-outline:{ .good_to_know } [HangFire](https://www.hangfire.io/)
- :material-lightning-bolt:{ .alternative } Quartz.NET

## Monitoring & Telemetry

- :green_heart: OpenTelemetry
- :green_heart: Prometheus
- :green_heart: Graphana
- :material-emoticon-excited-outline:{ .good_to_know } [ELK Stack](https://www.elastic.co/elastic-stack)

## Containers

- :green_heart: [Docker](https://www.docker.com/)
- :material-lightning-bolt:{ .alternative } [Podman](https://podman.io/)
- :material-lightning-bolt:{ .alternative } [Rancher](https://rancherdesktop.io/)
- Orchestration
    - :green_heart: [Docker Compose](https://docs.docker.com/compose/)
    - :green_heart: [Kubernetes](https://kubernetes.io/)
- Tooling
    - :green_heart: Minikube
    - :green_heart: [K9s](https://k9scli.io/)
    - :material-lightning-bolt:{ .alternative } [Lens](https://k8slens.dev/)
    - :material-lightning-bolt:{ .alternative } [Skaffold](https://skaffold.dev/)

## Cloud

- Providers
    - :green_heart: Azure
    - :green_heart: AWS
- Serverless
    - :green_heart: Azure Functions
    - :green_heart: AWS Lambda
- Storage
    - :green_heart: Azure Storage
    - :green_heart: AWS S3

## CI/CD (Continuous Integration & Deployment)

- :green_heart: GitHub Actions
- :material-emoticon-excited-outline:{ .good_to_know } TeamCity
- :material-emoticon-excited-outline:{ .good_to_know } Azure Pipelines
- :material-emoticon-excited-outline:{ .good_to_know } Jenkins
- :material-lightning-bolt:{ .alternative } Bamboo
- :material-lightning-bolt:{ .alternative } GitLab CI
- :material-lightning-bolt:{ .alternative } Octopus Deploy
- Build Automation
    - :material-emoticon-excited-outline:{ .good_to_know } [Nuke](https://nuke.build/) Build
    - :green_heart: [Cake](https://cakebuild.net/)

## .NET Libraries

- :green_heart: [Polly](https://github.com/App-vNext/Polly) .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner
- :green_heart: [FluentValidation](https://github.com/FluentValidation/FluentValidation) .NET validation library for building strongly-typed validation rules.
- :green_heart: [Humanizer.Core](https://github.com/Humanizr/Humanizer) Manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities
- :green_heart: [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet) .NET library for benchmarking
- :green_heart: [MediatR](https://github.com/jbogard/MediatR) Simple, unambitious mediator implementation in .NET
- :green_heart: [Units.NET](https://github.com/angularsen/UnitsNet) Makes life working with units of measurement just a little bit better

## DevOps

- Infrastructure as Code
    - :green_heart: [TerraForm](https://www.terraform.io/) Infrastructure automation to provision and manage resources in any cloud or data center
    - :material-lightning-bolt:{ .alternative } [Pulumi](https://www.pulumi.com/) Infrastructure as code in any programming language
    - :material-lightning-bolt:{ .alternative } Ansible

## Learning Resources and Community

- :green_heart: Official Microsoft Documentation, .NET Developer Blogs
- :green_heart: Community Forums: Stack Overflow, GitHub Discussions, Reddit
