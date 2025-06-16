# Doctor-Chatbot
# 🧠 Context-Aware Chatbot for Personal Healthcare Assistance using LLMs and LangChain

This repository hosts the implementation of a context-aware conversational chatbot designed for **personalized medical assistance** using **Large Language Models (LLMs)**, specifically **OpenAI’s GPT-3.5-turbo**, integrated with the **LangChain framework** and Retrieval-Augmented Generation (RAG). 

> 🏥 This project addresses key challenges in delivering real-time, privacy-preserving, and context-aware conversational support for non-emergency healthcare queries.

---

## 🚀 Key Features

- ✅ **Context-aware dialogue management** using LangChain memory buffers
- ✅ **RAG-based architecture** for grounding answers with relevant medical documents
- ✅ **Structured prompt engineering** (Chain-of-Thought reasoning) for multi-step medical queries
- ✅ **Modular LangChain chains** for intent recognition, retrieval, and response synthesis
- ✅ **Evaluaion using LangChain and LangSmith platforms** for evaluating contextual accuracy

---

## 📌 Motivation

Despite the rise of LLMs, using them safely and effectively for **medical domain** tasks requires domain-specific data grounding, controlled generation, and continuity in conversation. This project explores these challenges and proposes a robust architecture that combines modern LLM capabilities with:

- 💬 Natural language understanding for patient inputs
- 📚 Integration with authenticated healthcare documents
- 🧠 Context retention for improved conversational flow

---

## 🛠 Tech Stack

| Component             | Description                                       |
|-----------------------|---------------------------------------------------|
| 💡 LLM                | OpenAI GPT-3.5 Turbo via API                      |
| 🔗 LangChain          | Framework for chaining and memory handling        |
| 📚 Vector DB          | ChromaDB for document retrieval           |
| 🧠 Prompt Engineering | CoT prompts for structured and step-wise answers  |
| 📁 Data               | HealthBoards, Icliniq Custom Medical PDFs (via RAG)   |

---
