# Software Design Architectural Patterns

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
