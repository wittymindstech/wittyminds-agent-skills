---
name: rag-architecture
description: Design and review retrieval-augmented generation systems, including ingestion, parsing, chunking, embeddings, indexing, retrieval, reranking and grounded generation.
---

# RAG Architecture

## Objective
Design reliable, secure and measurable retrieval-augmented generation pipelines.

## Pipeline
1. Ingest authorized source documents.
2. Parse text, tables and layout; preserve source metadata.
3. Clean and normalize content without losing meaning.
4. Chunk according to document structure and retrieval goals.
5. Generate embeddings with a model appropriate to the corpus and language.
6. Index vectors, text and metadata in a suitable search system.
7. Embed or otherwise represent the user query consistently with the index.
8. Retrieve candidates using vector, lexical or hybrid search.
9. Apply metadata filters and access-control filters.
10. Rerank when evaluation shows a benefit.
11. Build a context window with source references.
12. Generate an answer constrained by retrieved evidence.
13. Validate citations, answer relevance and unsupported claims.
14. Monitor retrieval quality, latency, cost and failures.

## Design considerations
Discuss chunk size and overlap, embedding dimensions, index lifecycle, tenant isolation,
document freshness, deletion propagation, query rewriting, top-k, reranking, caching,
latency budgets and evaluation datasets.

## Rules
Do not assume one vector database or similarity metric is best for every workload.
Preserve document-level authorization throughout retrieval.
Do not fabricate citations or source content.

## Output
Return architecture, data flow, component choices, trade-offs, risks,
evaluation plan and operational metrics.
