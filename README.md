# Software Design Architectural Patterns

Software architectural patterns are reusable solutions and best practices for organizing software system architecture. Key patterns include MVC (Model-View-Controller), Microservices, Layered Architecture, Event-Driven Architecture, CQRS (Command Query Responsibility Segregation), Hexagonal Architecture, and Service-Oriented Architecture. These patterns are documented by Microsoft Azure Architecture Center, AWS Well-Architected Framework, Martin Fowler, and the broader software engineering community.

**URL:** [https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/apis.yml)

## Tags

- Best Practices
- Design Patterns
- Software Architecture
- System Design
- Microservices
- MVC
- CQRS
- Event-Driven

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Azure Architecture Center

Microsoft Azure Architecture Center provides guidance, patterns, and best practices for building cloud-native architectures. It documents CQRS, Event Sourcing, Strangler Fig, Circuit Breaker, Bulkhead, and Retry patterns with implementation guidance.

**Tags:** Cloud Architecture, Architectural Patterns, Microsoft Azure, Best Practices

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/architecture/patterns/)
- [Website](https://learn.microsoft.com/en-us/azure/architecture/)
- [JSON Schema](json-schema/architectural-pattern-schema.json)
- [JSON Structure](json-structure/architectural-pattern-structure.json)

### Microservices.io Patterns Catalog

Microservices.io is a pattern language for microservices architectures, documenting patterns for decomposition, data management, communication, deployment, and cross-cutting concerns.

**Tags:** Microservices, Architectural Patterns, API Gateway, Event Sourcing, CQRS

#### Properties

- [Documentation](https://microservices.io/patterns/)
- [Website](https://microservices.io/)

## JSON Schema

| Schema | Description |
|---|---|
| [architectural-pattern-schema.json](json-schema/architectural-pattern-schema.json) | JSON Schema for documenting a software architectural pattern with components, use cases, and tradeoffs |

## JSON Structure

| Structure | Description |
|---|---|
| [architectural-pattern-structure.json](json-structure/architectural-pattern-structure.json) | Structure documentation for ArchitecturalPattern and Component resources |

## JSON-LD

| Context | Description |
|---|---|
| [software-design-architectural-patterns-context.jsonld](json-ld/software-design-architectural-patterns-context.jsonld) | Linked data context mapping architectural pattern concepts to schema.org |

## Examples

| Example | Description |
|---|---|
| [cqrs-pattern-example.json](examples/cqrs-pattern-example.json) | Complete documentation of the CQRS architectural pattern including components, use cases, and tradeoffs |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [software-design-architectural-patterns-vocabulary.yml](vocabulary/software-design-architectural-patterns-vocabulary.yml) | Vocabulary covering architectural styles, decomposition patterns, integration patterns, and data patterns |

## Key Architectural Patterns Covered

### Architectural Styles
- **Layered Architecture** — N-tier structure with Presentation, Business Logic, and Data Access layers
- **Microservices Architecture** — Independently deployable services organized around business capabilities
- **Event-Driven Architecture** — Components communicate via events for loose coupling and async processing
- **MVC (Model-View-Controller)** — Separates data, UI, and control logic
- **CQRS** — Separates read (query) and write (command) models
- **Hexagonal Architecture** — Ports and Adapters pattern isolating application core
- **Serverless Architecture** — Functions-as-a-service for stateless, auto-scaling workloads

### Integration Patterns
- **API Gateway** — Single entry point for microservices backends
- **Saga Pattern** — Distributed transaction management via local transactions and events
- **Circuit Breaker** — Resilience pattern preventing cascading failures
- **Event Sourcing** — State as an append-only sequence of events

## Common Properties

- [Wikipedia: Architectural Patterns](https://en.wikipedia.org/wiki/Architectural_pattern)
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/patterns/)
- [Microservices.io](https://microservices.io/patterns/)
- [Refactoring.Guru](https://refactoring.guru/design-patterns)
- [Martin Fowler Architecture](https://martinfowler.com/architecture/)
