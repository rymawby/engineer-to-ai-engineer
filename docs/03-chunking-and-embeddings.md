# Chunking and Embeddings

Chunking and embeddings decide what knowledge can be retrieved, how precisely it can be retrieved, and how much useful context fits into a model call.

## Concepts To Know

- Text to vector concepts
- Why chunking matters
- Chunk size trade-offs
- Chunk overlap
- Embedding dimensionality
- Why changing models requires re-embedding

## Revision Prompts

- Why not embed an entire document as one vector?
- What happens when chunks are too small?
- What happens when chunks are too large?
- Why use overlap between chunks?
- What does embedding dimensionality affect?
- Why do stored vectors become incompatible when you change embedding model?

## Interview Angle

Chunking is an information-design problem, not just a preprocessing step. Better chunks often improve retrieval more than changing the generation prompt.

