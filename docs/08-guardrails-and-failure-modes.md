# Guardrails and Failure Modes

AI systems need guardrails because model output is probabilistic, tool calls can have side effects, and user input can be adversarial.

## Concepts To Know

- Hallucinations
- Tool misuse
- Infinite loops
- Prompt injection
- Schema validation
- Human approval workflows

## Revision Prompts

- What is a hallucination in a production system?
- How can a model misuse a tool?
- How do agent loops become infinite or wasteful?
- What is prompt injection?
- Why validate model output against schemas?
- When should a human approve an action before it runs?

## Interview Angle

Guardrails should sit outside the model as much as possible. Prompts help, but validation, permissions, rate limits, approvals, and deterministic checks are usually more reliable.

