# Migration Plan

## Overview
This document describes the migration from the local RAG system to a cloud-based architecture.

## Key Migration Changes

| Component | Old System | New System |
|-----------|------------|------------|
| Vector Database | ChromaDB | Upstash Vector |
| Embeddings | Ollama | Upstash Built-in |
| LLM | Ollama | Groq API |
| Infrastructure | Local | Cloud |

## Benefits of Migration

- Faster response time
- Cloud scalability
- Lower local hardware requirements
- Improved semantic search
