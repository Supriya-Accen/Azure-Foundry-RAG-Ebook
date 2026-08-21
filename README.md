# Azure AI Foundry RAG Agent: Inspire to Dream

## Overview

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) Agent using **Microsoft Foundry**, **Foundry IQ**, **Azure AI Search**, and **Azure OpenAI Embeddings**.

### Use Case

Developed a "Dream Inspire Coach" agent that answers motivational and goal-oriented questions using content from:

- The Story of My Life by Helen Keller
- A Little Princess by Frances Hodgson Burnett

### Key Features

- Agent creation using Microsoft Foundry
- Knowledge grounding using Foundry IQ
- Azure Blob Storage for document storage
- Azure AI Search for indexing and retrieval
- Vector embeddings using text-embedding-3-small
- Grounded responses with source citations
- Trace-based validation of retrieval workflow

  ### Outcomes

- Successfully indexed and vectorized source documents
- Connected Azure AI Search with Foundry IQ
- Enabled semantic retrieval for agent responses
- Verified knowledge retrieval through traces
- Generated responses with citations from source documents

### Skills Demonstrated

- Generative AI
- Retrieval-Augmented Generation (RAG)
- Microsoft Foundry
- Foundry IQ
- Azure AI Search
- Azure OpenAI Embeddings
- Vector Search
- Prompt Engineering
- Knowledge Grounding

## Solution Architecture

```text
E-books (TXT Files)
        │
        ▼
Azure Blob Storage
        │
        ▼
Azure AI Search
        │
        ▼
text-embedding-3-small
(Vector Embeddings)
        │
        ▼
Foundry IQ Knowledge Base
        │
        ▼
Microsoft Foundry Agent
        │
        ▼
GPT-5-mini
        │
        ▼
Grounded Responses with Citations




