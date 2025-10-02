# Conversational AI ChatBot for University 🤖

An intent-based conversational Chatbot specially for University related queries powered by a Small Language Model (SLM) and Retrieval-Augmented Generation (RAG).
The system intelligently classifies user queries, routes them to the right response generator, and delivers accurate, context-aware answers.

# Features

- Intent Classification – Uses a lightweight transformer model (T5-small) to detect user intent.

- Dual Response System:

     - Direct response from SLM for simple intents.

     - RAG pipeline (Gemini Pro + Sentence BERT embeddings + ChromaDB) for knowledge-grounded answers.

- Scalable & Modular – Easy to extend with new intents, knowledge sources, or APIs.

- Open-Source Friendly – Built using Hugging Face models, ChromaDB, and Python.

# Project Architecture

<img width="5787" height="5523" alt="Architecture" src="https://github.com/user-attachments/assets/d465c84b-fcf2-42b4-83d4-b251011086d0" />

# ⚙️Tech Stack

- Language Models: T5-small (SLM), Gemini Pro (LLM)

- Vector DB: ChromaDB

- Embeddings: Sentence BERT Embeddings

- Frameworks: LangChain, Hugging Face Transformers

- Database: SQLite (for data storage)

- Language: Python







