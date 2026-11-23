# 05 - Grounded Generation & Faithfulness Evaluation

## Source Summary
- **Topic:** Generating Verifiable Answers & Checking Quality
- **Key Takeaway:** The LLM synthesizes an answer strictly from retrieved chunks, and evaluation checks both retrieval relevance and answer faithfulness.

## Core Concepts
1. **Prompt Grounding:** The system prompt instructs the LLM: *"Answer using only the provided context. If the answer is not in the context, say you do not know."*
2. **Citations & Auditability:** Because answers trace back to specific retrieved chunks, users can verify where every claim came from.
3. **Two-Part Evaluation:**
   - *Context Relevance:* Did the retriever fetch the right chunks?
   - *Faithfulness (Groundedness):* Did the LLM stick strictly to the retrieved chunks without inventing extra claims?

## Cross-Links
- Previous: [04 - Retrieval & Similarity Ranking](04-retrieval-ranking.md)
- Back to Index: [Wiki Home](index.md)
