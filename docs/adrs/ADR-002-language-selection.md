# ADR-002: Language Selection for Cloud Ingestion and Edge Processing

## Status
Accepted

## Context
The system consists of:
- A modular monolith core platform
- A cloud-based ingestion microservice
- An edge IoT processing agent

We want:
- Cloud-native scalability
- Efficient concurrency
- Safe and reliable edge execution
- Opportunity to learn new technologies

## Decision
- Go will be used for cloud ingestion services.
- Rust will be used for the edge processing agent.

## Rationale

### Go (Cloud)
- Strong concurrency model (goroutines)
- Excellent support for HTTP/gRPC
- Simple deployment (static binaries, containers)
- Widely adopted in cloud-native ecosystems

### Rust (Edge)
- Memory safety without garbage collection
- High performance
- Strong reliability for long-running edge processes
- Growing adoption in embedded and IoT systems

## Consequences

Positive:
- Clear separation of concerns (cloud vs edge)
- High performance and safety guarantees
- Portfolio differentiation

Negative:
- Increased build complexity
- Multi-language CI/CD
- Learning curve for Rust