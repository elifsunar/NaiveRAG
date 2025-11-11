# NaiveRAG
A concise demonstration of a Naive (2-Step) Retrieval-Augmented Generation (RAG) pipeline using LangChain

This repository demonstrates a **Naive (2-Step) RAG** pipeline built using **LangChain**, **Hugging Face Embeddings**, and **ChromaDB**.  
The project illustrates the core principles of RAG: retrieving relevant context from a vector database and generating grounded responses using a large language model (LLM).

---

In a **Naive or 2-Step RAG architecture**, the workflow is divided into two main stages:

1. **Retrieval** — The system searches for semantically relevant text chunks from a knowledge base using vector similarity.
2. **Generation** — A language model generates an answer using only the retrieved context, ensuring factual and grounded responses.

---
