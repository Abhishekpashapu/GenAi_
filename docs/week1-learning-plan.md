# 🚀 GenAI Full Stack Engineering – 1 Week Intensive Bootcamp

> **Objective:** Cover the complete GenAI Full Stack roadmap in **7 intensive days**. This plan is designed to provide a solid understanding of each topic and culminates in building an end-to-end AI application.

> **Recommended Study Time:** **10–12 Hours/Day**

---

# 📅 Day 1 – Foundations of AI & Deep Learning

## 🎯 Goal

Understand the fundamentals of Artificial Intelligence, Deep Learning, and Computer Vision.

---

## 📖 Topics

### Artificial Intelligence

- What is Artificial Intelligence?
- AI vs Machine Learning vs Deep Learning vs Generative AI
- Discriminative Models vs Generative Models
- Industry Use Cases
  - Healthcare
  - Finance
  - Manufacturing
  - Retail
  - Education

---

### Deep Learning

- Neural Networks
- Perceptrons
- Layers
- Activation Functions
- Forward Propagation
- Backpropagation
- Loss Functions
- Gradient Descent
- SGD
- Adam
- AdamW

---

### Frameworks

- PyTorch Basics
- TensorFlow Basics
- Tensor Operations

---

### Computer Vision

- CNN Architecture
- Feature Extraction
- Pooling
- Convolution Layers

---

## 🛠 Hands-on

- Install Python
- Install PyTorch
- Install TensorFlow
- Create CNN Image Classifier

---

## 📂 Project

```
01_cnn_image_classifier.ipynb
```

---

# 📅 Day 2 – Generative Vision & Transformers

## 🎯 Goal

Learn how modern Generative AI models work.

---

## 📖 Topics

### Variational Autoencoders

- Encoder
- Decoder
- Latent Space
- KL Divergence

---

### GANs

- Generator
- Discriminator
- Minimax Loss
- DCGAN
- CycleGAN
- StyleGAN

---

### Diffusion Models

- Stable Diffusion
- Latent Diffusion
- Noise Scheduler
- ControlNet

---

### Transformers

- Attention Mechanism
- Scaled Dot Product Attention
- Multi Head Attention
- Positional Encoding
- Encoder
- Decoder
- GPT
- BERT
- T5
- RoPE
- KV Cache

---

### Prompt Engineering

- System Prompts
- User Prompts
- Zero Shot
- Few Shot
- Chain of Thought
- Tree of Thought
- Directional Prompting

---

## 🛠 Hands-on

- Prompt Chaining
- Transformer Playground

---

## 📂 Project

```
03_structured_prompt_chaining.py
```

---

# 📅 Day 3 – Open Source LLMs & Fine-Tuning

## 🎯 Goal

Understand open-source LLMs and parameter-efficient fine-tuning.

---

## 📖 Topics

### Hugging Face

- Hugging Face Hub
- Datasets
- Pipelines
- Transformers Library

---

### Open Source Models

- Llama 3
- Mistral
- Phi
- Qwen
- Gemma

---

### Quantization

- FP32
- FP16
- INT8
- INT4
- GGUF
- GPTQ
- AWQ

---

### Fine-Tuning

- Full Fine-Tuning
- PEFT
- LoRA
- QLoRA
- SFT
- Dataset Preparation

---

## 🛠 Hands-on

- Hugging Face Summarizer
- LoRA Demo

---

## 📂 Projects

```
04_huggingface_text_summarizer.ipynb

05_qlora_llama3_finetuning.ipynb
```

---

# 📅 Day 4 – Embeddings, Vector Databases & RAG

## 🎯 Goal

Learn Retrieval-Augmented Generation from scratch.

---

## 📖 Topics

### Embeddings

- Semantic Embeddings
- Cosine Similarity
- Dot Product
- Euclidean Distance

---

### Vector Databases

- ChromaDB
- FAISS
- Pinecone
- Qdrant

---

### RAG

- Document Loading
- Text Splitting
- Chunking
- Embeddings
- Indexing
- Retrieval
- Prompt Construction

---

### Advanced RAG

- Hybrid Search
- BM25
- Dense Retrieval
- Re-ranking
- Context Compression
- Metadata Filtering

---

## 🛠 Hands-on

Build a PDF Chatbot

---

## 📂 Project

```
06_rag_pdf_assistant.py
```

---

# 📅 Day 5 – LangChain, LlamaIndex & AI Agents

## 🎯 Goal

Build AI workflows and autonomous agents.

---

## 📖 Topics

### LangChain

- LCEL
- Prompt Templates
- Chains
- Memory
- Output Parsers

---

### LlamaIndex

- Document Loading
- Data Connectors
- Indexes
- Query Engines

---

### AI Agents

- ReAct
- Planning
- Tool Calling
- Function Calling
- Memory

---

### Multi-Agent Frameworks

- LangGraph
- CrewAI
- AutoGen

---

### MCP

- Model Context Protocol
- MCP Server
- MCP Client
- Tool Integration

---

## 🛠 Hands-on

Build Multi-Agent Research Assistant

---

## 📂 Project

```
07_multi_agent_researcher.py
```

---

# 📅 Day 6 – Evaluation, Guardrails & Deployment

## 🎯 Goal

Learn how production AI systems are evaluated and deployed.

---

## 📖 Topics

### Evaluation

- Ragas
- Faithfulness
- Context Precision
- Context Recall
- Answer Relevance

---

### Observability

- LangSmith
- Phoenix
- Tracing
- Token Usage
- Latency Monitoring

---

### Guardrails

- Prompt Injection
- Jailbreak Protection
- PII Masking
- Output Filtering

---

### Deployment

- FastAPI
- Streamlit
- Docker
- Docker Compose
- Ollama
- vLLM
- TensorRT-LLM

---

## 🛠 Hands-on

Dockerize a FastAPI Application

---

## 📂 Project

```
09_dockerized_rag_fastapi_app/
```

---

# 📅 Day 7 – Enterprise Capstone Project

## 🎯 Goal

Integrate everything learned into a single production-ready application.

---

# 🚀 Build

## Enterprise PDF RAG Assistant

---

## Features

- PDF Upload
- OCR Support (Optional)
- Text Extraction
- Chunking
- Embeddings
- Vector Database
- Retrieval
- OpenAI / Llama Integration
- Chat Interface
- Memory
- Source Citations
- FastAPI Backend
- Streamlit Frontend
- Docker Deployment

---

## Bonus Features

- Multi Document Support
- Multi-Agent Workflow
- LangSmith Monitoring
- User Authentication
- Logging
- Evaluation Dashboard

---

## 📂 Final Project

```
enterprise_pdf_rag/

├── backend/
├── frontend/
├── ingestion/
├── embeddings/
├── vector_db/
├── llm/
├── rag/
├── agents/
├── evaluation/
├── deployment/
└── docker/
```

---

# 📅 Daily Schedule

| Time | Activity |
|------|----------|
| 08:00 – 10:00 | Theory |
| 10:00 – 12:00 | Documentation |
| 12:00 – 01:00 | Break |
| 01:00 – 04:00 | Coding |
| 04:00 – 06:00 | Hands-on Project |
| 06:00 – 07:00 | Break |
| 07:00 – 09:00 | Revision & Notes |
| 09:00 – 10:00 | GitHub Commit & README Update |

---

# 📚 Resources

## Documentation

- Python Documentation
- PyTorch Documentation
- TensorFlow Documentation
- Hugging Face Documentation
- LangChain Documentation
- LlamaIndex Documentation
- FastAPI Documentation
- Docker Documentation
- OpenAI API Documentation

---

# ✅ Deliverables

- CNN Image Classifier
- Prompt Chaining Project
- Hugging Face Summarizer
- QLoRA Fine-Tuning Demo
- PDF RAG Assistant
- Multi-Agent Research Assistant
- Dockerized FastAPI App
- Enterprise PDF RAG Chatbot
- Complete GitHub Repository
- Project Documentation

---

# 🏆 Final Outcome

After completing this bootcamp, you will have hands-on exposure to:

- Artificial Intelligence
- Deep Learning
- Computer Vision
- Transformers
- Prompt Engineering
- OpenAI APIs
- Hugging Face Ecosystem
- Fine-Tuning with LoRA & QLoRA
- Embeddings & Vector Databases
- Retrieval-Augmented Generation (RAG)
- LangChain & LlamaIndex
- AI Agents & Multi-Agent Systems
- Model Context Protocol (MCP)
- LLM Evaluation & Observability
- AI Guardrails & Security
- FastAPI Deployment
- Docker & Production MLOps
- Enterprise GenAI Application Development