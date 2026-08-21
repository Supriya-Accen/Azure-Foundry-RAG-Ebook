# Azure AI Foundry RAG Agent: Inspire to Dream

## Overview

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) Agent using **Microsoft Foundry**, **Foundry IQ**, **Azure AI Search**, and **Azure OpenAI Embeddings**.

The agent is designed to inspire users and answer questions using content from two public-domain books:

- *The Story of My Life* by Helen Keller
- *A Little Princess* by Frances Hodgson Burnett

The solution uses semantic search and vector embeddings to retrieve relevant content from the books and generate grounded responses with citations.

---

## Business Scenario

Users often seek motivation, guidance, and inspiration when facing challenges.

This agent acts as a **Dream Inspire Coach**, leveraging inspirational stories and life lessons from classic literature to provide:

- Goal-setting guidance
- Motivation and encouragement
- Lessons on perseverance
- Strategies for overcoming obstacles
- Inspirational examples from real-world and fictional characters

---

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
