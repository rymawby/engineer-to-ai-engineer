# Distributed Systems Concepts

Many AI workflows are distributed systems: they call external APIs, run long jobs, retry work, and coordinate state across services.

## Concepts To Know

- Idempotency
- Retries
- Partial failures
- Saga pattern
- State machines
- Eventual consistency

## Revision Prompts

- Why does idempotency matter when retrying model or tool calls?
- What makes retries dangerous?
- What is a partial failure?
- How can a saga pattern help with multi-step workflows?
- Why model long-running workflows as state machines?
- Where might eventual consistency appear in an AI product?

## Interview Angle

AI engineering still depends on normal reliability engineering. A model may decide what to do, but the surrounding system must handle failure, recovery, duplication, and state.

