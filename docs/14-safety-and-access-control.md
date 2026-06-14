# Safety and Access Control

Safety in AI systems includes what data the model can see, what tools it can call, and what actions it is allowed to take.

## Concepts To Know

- ACL-aware retrieval
- Metadata filtering
- Preventing data leakage
- Restricting tool access

## Revision Prompts

- How should access control affect retrieval?
- What metadata would you filter on?
- How can data leak through retrieved context?
- Why restrict tools by user, role, workflow, or environment?

## Interview Angle

Never rely on the model to ignore data it should not have received. Enforce access control before retrieval, before tool calls, and before side effects.

