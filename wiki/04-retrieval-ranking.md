# 04 - Retrieval & Similarity Ranking

## Source Summary
- **Topic:** Finding the Top-K Most Relevant Chunks
- **Key Takeaway:** At query time, the user's question is embedded with the same model and compared against stored vectors using similarity metrics like cosine similarity.

## Core Concepts
1. **Query Embedding:** The user's question is converted into a query vector using the exact same embedding model used during indexing.
2. **Cosine Similarity Intuition:** Measures the angle between two vectors—smaller angle (score closer to 1.0) means closer meaning regardless of text length.
3. **Top-K Selection:** The vector database returns the top *k* (e.g., top 3 to 5) most relevant chunks to pass to the generator.
4. **Common Retrieval Failure:** If the query is vague or vocabulary mismatches heavily, irrelevant chunks can enter Top-K ("garbage in, garbage out").

## Cross-Links
- Previous: [03 - Embeddings & Vector Representations](03-embeddings-vectors.md)
- Next: [05 - Grounded Generation & Faithfulness Evaluation](05-grounded-generation-eval.md)
