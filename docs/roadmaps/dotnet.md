# :material-language-csharp: .NET Developer Roadmap
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
### CSharp
- 🟢 [CSharp 12](https://learn.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-12)
    - **Basic Syntax**: Variables, control flow (if, for, while), methods, classes, and interfaces.
    - **Advanced Features**: Generics, delegates, events, LINQ, async/await.
    - **Error Handling**: Exception handling using try, catch, finally blocks.
    - **Data Types**: Understanding value types vs. reference types, nullable types, tuples, and records.
    - **Latest Enhancements**: Records, top-level statements, pattern matching enhancements.
- 🟢 [.NET 8](https://learn.microsoft.com/en-us/dotnet/core/whats-new/dotnet-8/overview)
- 🟢 [.NET CLI](https://learn.microsoft.com/en-us/dotnet/core/tools/)
- 🔵 [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-overview)
    - [Apir8](https://prom3theu5.github.io/aspirational-manifests/getting-started.html)
### Architecture
- 🟢 [SOLID](https://learn.microsoft.com/en-us/archive/msdn-magazine/2014/may/csharp-best-practices-dangers-of-violating-solid-principles-in-csharp) Principles
    - Single responsibility
    - Open-closed
    - Liskov substitution
    - Interface Segregation
    - Dependency Inversion
- 🟢 MVC - Model View Controller
- 🟢 MVVM - Model View ViewModel
- 🟢 [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- 🟢 [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
- 🟢 [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- 🟢 Design Patterns (Gang of Four)
- 🟢 Microservices Architecture: Patterns and Best Practices (e.g., CQRS, Event Sourcing)
- 🔵 [Clean](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#clean-architecture) (Onion) Architecture and Domain-Driven Design (DDD)
- 🔵 [Vertical](https://medium.com/@v.cheshmi/introduction-ae32b9f32ac5) [Slice Architecture](https://blog.ndepend.com/vertical-slice-architecture-in-asp-net-core/)
### ASP.NET Core
- 🟢 [Web API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-8.0&tabs=visual-studio)
- 🟢 [Minimal API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio)
- 🟢 [Routing](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-8.0)
- 🟢 [Middleware](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-8.0)
- 🟢 [Filters](https://learn.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-8.0)
- 🟢 [Configuration](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-8.0)
- Authentication
    - 🟢 [JWT](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/jwt-authn?view=aspnetcore-8.0&tabs=windows)
    - 🟢 [Basic Auth](https://learn.microsoft.com/en-us/aspnet/web-api/overview/security/basic-authentication)
    - 🟢 Token Auth
    - 🟢 OAuth
    - 🟢 Cookies
    - 🔵 OpenID
    - 🔵 SAML
- 🔵 IdentityServer/Duende IdentityServer for implementing these protocols
- 🟢 Authorization
- 🟢 Dependency Injection
- 🔵 Integrating with modern JavaScript frameworks (React, Angular, Vue)
### RDBMS Databases
- 🟢 RDBMS Fundementals
- 🟢 SQL Syntax
- ⛔ Stored procedures
- ⛔ Triggers
- Vendor specific databases
    - 🟢 PostgreSQL
    - 🟢 SQL Server
    - 🔵 MySQL/MariaDB
    - ⛔ Oracle
### APIs
- 🟢 REST
    - 🟢 Minimal API
    - 🟢 Web API
    - 🟣 [FastEndpoints](https://fast-endpoints.com/)
- 🔵 GraphQL
    - 🟢 [HotChocolate](https://chillicream.com/docs/hotchocolate/v13)
- 🔵 gRPC
### ORMs
- 🟢 [Dapper](https://github.com/DapperLib/Dapper)
- 🟢 Entity Framework Core
    - EF Basics
    - Code first
    - Migrations
    - Change tracker API
    - Loading modes
    - Interceptors
- 🟣 [RepoDB](https://repodb.net/)
- ⛔ NHibernate
### Dependency Injection
- 🟢 Microsoft.Extensions.DependencyInjection
- 🔵 [Scrutor](https://github.com/khellang/Scrutor)
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
    - Stackexchange.Redis
- 🟢 Output caching
- ⛔ Response caching
### Logging
- 🟢 Microsoft.Extensions.Logging
- 🟢 Serilog
- 🔵 NLog
- ⛔ Log4Net
### Messaging
- 🟢 Azure Service Bus
- 🟢 AWS SQS/SNS
- 🟢 [MassTransit](https://masstransit.io/)
- 🟢 RabbitMQ
- 🟣 [Wolverine](https://wolverine.netlify.app/)
- ⛔ NServiceBus
### Security
- 🟢 Secure coding practices
- 🟢 Data protection
- 🟢 ASP.NET Core security features
### Front-End Technologies
- 🔵 Responsive Design: CSS, Bootstrap, Tailwind CSS
- 🔵 SPA frameworks: Angular, React, Vue.js with .NET backends
### Unit Testing
#### Frameworks
- 🟢 [NUnit](https://nunit.org/)
- 🟢 [xUnit](https://xunit.net/)
- ⛔ MsTest
#### Mocking
- 🟢 [NSubstitute](https://nsubstitute.github.io/)
- 🟢 [Moq](https://github.com/devlooped/moq)
- 🟣 [FakeItEasy](https://fakeiteasy.github.io/)
#### Assertions
- 🟢 [FluentAssertions](https://fluentassertions.com/)
- 🟣 [Shouldly](https://docs.shouldly.org/)
#### Test Data
- 🟢 [Bogus](https://github.com/bchavez/Bogus)
- 🟢 [AutoFixture](https://github.com/AutoFixture/AutoFixture)
### Integration Testing
- 🟢 WebApplicationFactory
    - TestContainers
    - Respawn
- 🟣 Postman
- 🟣 TestServer
### Snapshot Testing
- 🔵 [Verify](https://github.com/VerifyTests/Verify)
### E2E Testing
- 🔵 [Playwright](https://playwright.dev/)
- ⛔ Selenium
### Performance Testing
- 🟢 [K6](https://k6.io/)
- 🟣 [NBomber](https://nbomber.com/)
- 🟣 [JMeter](https://jmeter.apache.org/)
### Streaming
- 🔵 Apache Kafka
- 🟣 AWS Kinesis
- 🟣 Azure Event Hubs
### Real-Time Communication
- 🔵 SignalR
- 🔵 WebSockets
### API Documentation
- 🟢 OpenAPI
- 🔵 AsyncAPI
### API Libraries
- 🟢 [Refit](https://reactiveui.github.io/refit/)
- 🟢 [RestSharp](https://restsharp.dev/)
- 🟣 [Flurl](https://flurl.dev/)
### Task Scheduling
- 🟢 BackgroundService
- 🟢 PeriodicTimer
- 🔵 [HangFire](https://www.hangfire.io/)
- 🟣 Quartz.NET
### Monitoring & Telemetry
- 🟢 OpenTelemetry
- 🟢 Prometheus
- 🟢 Graphana
- 🔵 [ELK Stack](https://www.elastic.co/elastic-stack)
### Containers
- 🟢 [Docker](https://www.docker.com/)
- 🟣 [Podman](https://podman.io/)
- 🟣 [Rancher](https://rancherdesktop.io/)
- Orchestration
    - 🟢 [Docker Compose](https://docs.docker.com/compose/)
    - 🟢 [Kubernetes](https://kubernetes.io/)
- Tooling
    - 🟢 Minikube
    - 🟢 [K9s](https://k9scli.io/)
    - 🟣 [Lens](https://k8slens.dev/)
    - 🟣 [Skaffold](https://skaffold.dev/)
### Cloud
- Providers
    - 🟢 Azure
    - 🟢 AWS
- Serverless
    - 🟢 Azure Functions
    - 🟢 AWS Lambda
- Storage
    - 🟢 Azure Storage
    - 🟢 AWS S3
### CI/CD (Continuous Integration & Deployment)
- 🟢 GitHub Actions
- 🔵 TeamCity
- 🔵 Azure Pipelines
- 🔵 Jenkins
- 🟣 Bamboo
- 🟣 GitLab CI
- 🟣 Octopus Deploy
- Build Automation
    - 🔵 [Nuke](https://nuke.build/) Build
    - 🟢 [Cake](https://cakebuild.net/)
### .NET Libraries
- 🟢 [Polly](https://github.com/App-vNext/Polly) .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner
- 🟢 [FluentValidation](https://github.com/FluentValidation/FluentValidation) .NET validation library for building strongly-typed validation rules.
- 🟢 [Humanizer.Core](https://github.com/Humanizr/Humanizer) Manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities
- 🟢 [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet) .NET library for benchmarking
- 🟢 [MediatR](https://github.com/jbogard/MediatR) Simple, unambitious mediator implementation in .NET
- 🟢 [Units.NET](https://github.com/angularsen/UnitsNet) Makes life working with units of measurement just a little bit better
### DevOps
- Infrastructure as Code
    - 🟢 [TerraForm](https://www.terraform.io/) Infrastructure automation to provision and manage resources in any cloud or data center
    - 🟣 [Pulumi](https://www.pulumi.com/) Infrastructure as code in any programming language
    - 🟣 Ansible
### Learning Resources and Community
- 🟢 Official Microsoft Documentation, .NET Developer Blogs
- 🟢 Community Forums: Stack Overflow, GitHub Discussions, Reddit