# 02 - Document Chunking Strategies

## Source Summary
- **Topic:** Splitting Knowledge Sources for Accurate Retrieval
- **Key Takeaway:** Long documents exceed context limits and dilute semantic meaning; splitting them into focused, overlapping chunks improves retrieval precision.

## Core Concepts
1. **Why Chunking Matters:** Embedding a 50-page manual into one vector averages out every topic, making specific facts hard to match.
2. **Fixed-Size vs. Semantic Chunking:**
   - *Fixed-size with overlap* (e.g., 500 tokens with 50-token overlap) prevents sentences at boundaries from losing context.
   - *Structure-aware chunking* splits along Markdown headings or paragraphs so each chunk stays conceptually coherent.
3. **Chunk Size Trade-Off:**
   - Too small: loses surrounding context.
   - Too large: introduces irrelevant noise into the prompt.

## Cross-Links
- Previous: [01 - Why RAG?](01-why-rag.md)
- Next: [03 - Embeddings & Vector Representations](03-embeddings-vectors.md)
