# Use Microservices architecture

* Status: proposed
* Date: 2024-11-27

## Context and Problem Statement

Current monolithic architecture has issues with next quality attributes:
- Scalability
- Performance
- Availability
- Modifiability
- Deployability
- Testability
- Scaling teams
- Achieving desired time-to-market goals

## Considered Options

* Microservices architecture
* Modular monolith

## Decision Outcome

Chosen option: "Microservices architecture", because comes out best.

### Positive Consequences

* Scalability, Performance, Availability, achieving TTM

### Negative Consequences

* Need more skilled team
* Need budget to design observability platform

## Pros and Cons of the Options

### Microservices architecture

Adopting a microservices architecture based on bounded contexts will empower our organization to respond to changes in business requirements swiftly, enhance collaboration across teams, and ultimately deliver greater value to our customers. This architectural shift will set a foundation for sustainable growth and innovation in our software ecosystem.

* Good, because Scalability
* Good, because Deployability
* Good, because Testability
* Good, because Availability
* Good, because Bounded-contexted
* Bad, because Complexity
* Bad, because Distributed environemnt
* Bad, because Additional overhead
* Bad, because Requires advanced observability

### Modular monolith

* Good, because Single deployment unit
* Good, because Less distributed overhead
* Bad, because Single-point-of-failure
* Bad, because Scalability
* Bad, because Responsibility ownership
* Bad, because Deployment coordination
* Bad, because Availability
