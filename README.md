# 🚀 Projects Portfolio

A collection of projects focused on **Modern C++ programming and AI-driven applications**.  
The emphasis is on **clean architecture, scalability, and practical problem solving**.

---

## 📌 Current Projects

### 🛰️ Drone Tunnel Simulator (C++)
**Tech:** C++, OOP, Design Patterns, SOLID principles, Agile development methodology  

A modular drone simulation system designed for extensibility and performance.

- Implemented the **Command pattern** supporting 10+ operations (movement, sensing, navigation)
- Built around abstract components (`Command`, `Sensor`, `Tile`) enabling polymorphism
- Designed a **compile-time energy consumption decorator** for flexible behavior composition
- Developed interchangeable sensor modules with independent logic
- Focused on **scalable architecture and low-level control**

---

### 🎬 RAG-Based Movie Script Q&A System

Tech: Python, LLMs, Retrieval-Augmented Generation (RAG), Vector Search

Built an end-to-end question-answering system over full movie scripts, enabling natural language queries on long narrative texts
Implemented a RAG pipeline: script preprocessing → chunking → embedding → vector retrieval → answer generation
Designed the system to handle large, unstructured text (scripts) where traditional LLM context limits fail
Focused on retrieving relevant scenes/dialogue segments to ground responses and reduce hallucinations
Explored techniques for improving retrieval quality (chunking strategy, top-k selection, context construction)
Demonstrates practical use of RAG to combine information retrieval + generation for accurate, context-aware answers

Focus: Applied LLM systems, long-context handling, retrieval quality optimization

---

### 🔍 Research AI Agent

Tech: Python, LLMs, Information Retrieval, APIs, Telegram Bot

Built an end-to-end autonomous research assistant that transforms a user query into a structured research report
Implements a multi-step pipeline:
Query expansion (generates multiple search queries)
Retrieval from diverse sources (e.g., arXiv, Google Scholar, PubMed, GitHub)
Deduplication and ranking using BM25 over titles and abstracts
LLM-based analysis of top results
Produces concise, formatted research summaries and delivers them via a Telegram bot or REST API
Designed to reduce noise by filtering and ranking high-quality sources instead of naive search aggregation
Modular architecture (agent, bot, api) enabling extension to new data sources and workflows

Focus: Autonomous agents, retrieval pipelines, research automation, LLM-grounded analysis

---

## 🧩 Skills Demonstrated

- **Languages:** C++, Python
- **Core Concepts:**  
  - Object-Oriented Design  
  - Design Patterns  
  - SOLID principles
  - Agile development
- **Tools:** Git, Linux, APIs  
- **Focus Areas:**  
  - System Design  
  - Scalability  
  - Analytical Thinking  

---
