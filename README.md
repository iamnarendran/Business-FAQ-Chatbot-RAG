# 🤖 Business FAQ Chatbot – RAG + Open LLM

A simple Retrieval-Augmented Generation (RAG) chatbot that answers questions based on company FAQ documents. Built entirely using free tools like ChromaDB, SentenceTransformers, and OpenRouter LLMs — all runnable in Google Colab.

---

## 🧠 Features

- Upload or define custom FAQ content
- Embed using `sentence-transformers` (MiniLM)
- Store and retrieve using `ChromaDB` (in-memory)
- Generate LLM-based answers using `OpenRouter` (Deepseek, Mistral, etc.)
- Google Colab-compatible, no GPU or paid APIs needed

---

## 🧪 How It Works

1. Define or upload a plain-text FAQ document
2. Split into Q&A chunks and embed with `MiniLM`
3. Store in ChromaDB for vector search
4. Accept a user question
5. Retrieve the top-3 matching chunks
6. Send context + question to OpenRouter LLM
7. Display the generated answer

---

## 💻 Tech Stack

- 🧠 LLM: OpenRouter API (e.g. Deepseek)
- 🧾 Embedding: `sentence-transformers`
- 📦 Vector Store: `chromadb`
- ☁️ Runtime: Google Colab

---

## 🔍 Example Prompt

- Prompt: `Do you provide chatbot solutions & Can you build domain-specific LLM applications?`

- Response: `💬 Answer: Yes, we provide intelligent chatbot solutions and can build domain-specific LLM applications tailored for retail, HR, finance, and more. I'm a chatbot powered by Deepseek AI.`

- Prompt: `How many workers in your office?`
- Response: `💬 Answer: I don't have what you asked [how many workers in your office], please feel free to contact our email. I'm a chatbot powered by Deepseek AI.` 
---
