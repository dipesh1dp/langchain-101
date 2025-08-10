# LangChain-101 📚  

Welcome to **LangChain-101**, an educational repository designed to help you get hands-on with **LangChain** and **LangGraph**.  
This repo walks you from the absolute basics to building your own **chatbots** and **RAG (Retrieval-Augmented Generation)** applications.

> If you're new to LangChain or LangGraph, this is your starting point.  
> If you know the basics but want to see them in action — jump straight into the mini projects.

---

## 📂 Repository Structure

| Notebook | Description |
|----------|--------------|
| `01-A_beginer's_guide` | Learn the foundations — models, prompts, chains, streaming, and debugging tools. |
| `02-LangGraph_fundamentals` |  Understand LangGraph’s building blocks — State, Node, Edge, and Graph construction. |
| `03-Building_a_chatbot_with_memory` | Mini-project: Build a chatbot that remembers context across conversations. |
| `04-Building_RAG_Chatbot` | Mini-project: Upload a PDF and query it using Retrieval-Augmented Generation. |

---
## 🧠 What You'll Learn

### 01 — LangChain: A Beginner’s Guide
- **Loading Models** — Choosing & initializing LLMs.
- **Prompts** — `ChatMessage` & `ChatPromptTemplate`.
- **Runnables & LCEL** — LangChain Expression Language for chaining operations.
- **Chaining** — Combining multiple steps into workflows.
- **Streaming** — Real-time token streaming.
- **Guided Generation** — Providing context to steer model outputs.
- **Debugging** — `set_debug`, `set_verbose`, LangSmith tracing, and `astream_events`.

---

### 02 — LangGraph Fundamentals
- **Introduction to LangGraph**
- **Core Concepts**:
  - **State** — Managing dynamic data in the graph.
  - **Node** — A functional step in the workflow.
  - **Edge** — The link between nodes.
- **Graph Construction & Invocation**
- **Your First LangGraph** — Step-by-step example.

---

### 03 — Building a Chatbot with Memory 🗨️
- Persistent memory for conversational context.
- Manage message history
- Example: Create a bot that *remembers what you said earlier*.

---

### 04 — Building a RAG Chatbot (PDF QA) 📄
- Load and chunk PDFs.
- Use vector stores to retrieve relevant chunks.
- Integrate retrieval with the chatbot.
- Ask questions directly from the documents.

---

## Getting Started
**1. Clone this repository**
```bash
git clone https://github.com/dipesh1dp/langchain-101.git
cd langchain-101
``` 
**2. Install dependencies**
```bash 
pip install -r requirements.txt
``` 
**3. Run the notebooks**
You can run the notebooks in:
- Jupyter Notebook
- VS Code with Jupyter extension
- Google Colab (upload notebooks)

## 📖 Prerequisites
- Python knowledge 
- Familiarity with Large Language Models (LLMs) is a plus, but not required.
- Familiarity with vector database and similarity search is a plus, but not required.
- Installed Jupyter or Google Colab access.

## 📌 Future Plans
- Adding LangChain Agents tutorial.
- Integrating LangServe for deployment.
- More mini-projects with APIs & tools.

**🛠️ Maintained by**
[Dipesh Pandit](https://github.com/dipesh1dp) — AI/ML Enthusiast

If you find this helpful, ⭐ the repo!
