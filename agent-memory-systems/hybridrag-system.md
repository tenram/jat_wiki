# HybridRAG: Combining Knowledge Graphs and Vector Retrieval

> Sources: Abhishek Biswas, Unknown date
> Raw: [Building a HybridRAG System](../../raw/agent-memory-systems/hybridrag-system.md)

## Overview

A retrieval architecture combining VectorRAG (embedding similarity search) and GraphRAG (structured entity/relationship queries) into one pipeline, aiming to cover both fact-lookup (extractive) and synthesis-style (abstractive) queries better than either method alone.

## Pipeline

Documents are chunked (1024 tokens, 200-token overlap), embedded with `text-embedding-ada-002` (1536-dim), and stored in Chroma. In parallel, a two-stage prompting process extracts entities and relationships into a Neo4j graph. At query time, results from both stores are merged into context passed to GPT-3.5 Turbo. LangChain orchestrates the pipeline; evaluation uses faithfulness and answer-relevance metrics.

This vector+graph combination is conceptually adjacent to memory systems like [OB1](ob1.md) (vector-centric) and [RightMemory](rightmemory.md) (graph/tree-centric); HybridRAG explicitly argues for combining both rather than choosing one.

## See Also

- [OB1](ob1.md)
- [RightMemory](rightmemory.md)
