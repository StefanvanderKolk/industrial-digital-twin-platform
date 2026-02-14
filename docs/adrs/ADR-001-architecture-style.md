# ADR-001: Architecture Style – Modular Monolith with Edge Ingestion Service

## Status
Accepted

## Context
The system must:
- Allow rapid iteration
- Support ML experimentation
- Simulate real-world industrial data ingestion
- Remain maintainable by a single developer

## Decision
We will implement:
- A modular monolith for the cloud platform
- A standalone ingestion service running at the edge

## Rationale
- Reduced operational complexity
- Clear domain boundaries
- Realistic industrial architecture
- Extractable services in the future

## Consequences

### Positive
- Fast iteration
- Lower DevOps overhead
- Clear module ownership

### Negative
- Single deployment unit for cloud
- Must enforce strong internal module boundaries

## Alternatives Considered
- Pure microservices architecture
- Full monolith
- Serverless ingestion