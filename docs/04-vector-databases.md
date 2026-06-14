# Vector Databases

Vector databases store embeddings and support similarity search, usually with indexes that make nearest-neighbour lookup fast enough for production systems.

## Concepts To Know

- What makes a database a vector database
- Cosine similarity
- k-nearest neighbour search
- ANN vs brute force
- HNSW vs IVF
- Latency vs recall vs cost
- pgvector vs Pinecone

## Revision Prompts

- What is a vector database optimised for?
- What does cosine similarity compare?
- What does top-k nearest-neighbour search return?
- Why use approximate nearest neighbour search instead of brute force?
- What are the trade-offs between HNSW and IVF-style indexes?
- When might pgvector be enough?
- When might a managed vector database such as Pinecone make sense?

## Interview Angle

The useful trade-off is not "which vector DB is best?" It is latency, recall, cost, operational complexity, data size, and how tightly vector search needs to live beside relational data.

