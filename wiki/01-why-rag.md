# 01 - Why RAG? Limitations of Standalone LLMs

## Source Summary
- **Topic:** Parametric Memory vs. External Knowledge
- **Key Takeaway:** Large Language Models (LLMs) rely on static weights frozen at training time, leading to outdated answers, private-data blindness, and hallucinations.

## Core Concepts
1. **Static Knowledge Cutoff:** A standalone LLM cannot answer questions about events or private documents created after its training cutoff without retraining or fine-tuning.
2. **Hallucination Risk:** When an LLM lacks relevant facts in its parameters, it may still generate fluent, confident-sounding misinformation.
3. **Why Fine-Tuning Alone Is Not Enough:** Fine-tuning teaches style and task patterns well, but updating rapidly changing facts via weights is expensive and hard to audit.
4. **The RAG Solution:** Instead of memorizing every fact inside model weights, RAG retrieves relevant evidence at query time and supplies it in the prompt context.

## Cross-Links
- Next: [02 - Document Chunking Strategies](02-chunking-strategy.md)
