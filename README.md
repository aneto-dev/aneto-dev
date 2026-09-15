# Aires Neto

### Senior Software Engineer

**Distributed Systems · .NET · Python · Cloud Architecture**

I’m a software engineer with 10+ years of experience, mainly working with C# and .NET on business-critical systems.

Most of my work has involved taking fairly complicated business processes and turning them into software that people can actually operate and support — order management, internal platforms, APIs, integrations, and the less visible parts of systems such as reliability, diagnostics, and production support.

More recently, I’ve been spending more time on distributed systems, domain-driven design, cloud architecture, Python, and AI engineering.

[Portfolio](https://aneto-dev.github.io/aires-portfolio/) · [LinkedIn](https://linkedin.com/in/aires-neto-2750b2b0)

---

## What I’m working on

### OrderForge

**Distributed commerce and fulfilment platform — currently in design and development**

OrderForge is my main portfolio project. I’m building it around the sort of problems that make commerce systems interesting beyond the storefront: orders, inventory reservations, payments, fulfilment, cancellations, returns, refunds, retries, duplicated messages, partial failure, and operational recovery.

The aim is to show the engineering decisions as much as the finished software — where consistency matters, where eventual consistency is acceptable, how workflows recover when something goes wrong, and how the system is observed and operated in production.

**Planned stack:** .NET · PostgreSQL · event-driven messaging · OpenTelemetry · Docker · Azure · Next.js

I’m developing it in stages, so I’ll publish architecture, code, tests, deployment evidence, and the public demo as those milestones are actually completed.

---

## Selected projects

### [OpsFlow](https://github.com/aneto-dev/opsflow)

A Django workflow approval engine built around reusable workflows, ordered approval steps, actor-based task assignment, and decision history.

**Python · Django · workflow design · access control · auditability**

### [EventFlow](https://github.com/aneto-dev/eventflow-event-driven-system)

A .NET project exploring the reliability concerns behind event-driven systems, including transactional outbox patterns, idempotent consumers, retries, and observability.

**.NET · RabbitMQ · PostgreSQL · OpenTelemetry**

### [.NET Observability API](https://github.com/aneto-dev/dotnet-observability-api)

An ASP.NET Core project focused on making application behaviour visible through traces, metrics, structured logs, and service diagnostics.

**.NET · OpenTelemetry · Prometheus · Grafana · Loki · Docker**

---

## How I like to build software

I’m most interested in systems where correctness and operability matter. That usually means thinking about things such as:

- domain boundaries and business rules
- distributed workflows and failure recovery
- consistency, concurrency, and idempotency
- API and backend platform design
- observability and production diagnostics
- automated testing and safe delivery
- incremental modernisation of existing systems

I try not to add technology just because it looks good on an architecture diagram. If a queue, cache, workflow engine, or extra service is there, it should be solving a problem that can be explained clearly.

---

## Technologies I work with

**Backend:** C# · .NET · ASP.NET Core · Python · Django  
**Data:** SQL Server · PostgreSQL · Redis  
**Architecture:** DDD · event-driven systems · distributed workflows · REST APIs  
**Observability:** OpenTelemetry · Prometheus · Grafana · Loki · Elasticsearch  
**Cloud & delivery:** Azure · Docker · CI/CD  
**Web:** TypeScript · Next.js · React

---

## What’s next

I’m rebuilding this portfolio around a smaller number of deeper projects rather than collecting lots of small demo applications.

OrderForge is the first flagship project. After that, I plan to add work around AI engineering and repository intelligence, followed by a dedicated observability and incident-operations platform.

The goal is for the repositories to show how I think about software, not just which technologies I’ve used.

---

## Contact

[Portfolio](https://aneto-dev.github.io/aires-portfolio/) · [LinkedIn](https://linkedin.com/in/aires-neto-2750b2b0)