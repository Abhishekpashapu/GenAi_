📚 Detailed Curriculum & Topics

### 🔹 Module 1: Foundations of AI & Deep Learning
* **GenAI vs. Traditional AI**: Discriminative vs. Generative models.
* **Industry Use Cases**: Applications across Finance, Healthcare, E-commerce, and Manufacturing.
* **Deep Learning Mechanics**:
  * Neural network architectures, Forward & Backpropagation, Loss functions.
  * Optimization algorithms: SGD, Adam, AdamW.
* **Framework Fundamentals**: Tensor operations in PyTorch and TensorFlow.
* **Computer Vision Architectures**: Convolutional Neural Networks (CNNs).
* 🛠️ **Hands-on Project**: `01_cnn_image_classifier.ipynb`

---

### 🔹 Module 2: Generative Vision & Latent Space Models
* **Variational Autoencoders (VAEs)**:
  * Latent space representation, Encoders/Decoders, KL-Divergence loss.
* **Generative Adversarial Networks (GANs)**:
  * Generator vs. Discriminator dynamics, Minimax game theory.
  * GAN Architectures: DCGAN, StyleGAN, CycleGAN.
* **Modern Generative Vision**:
  * Latent Diffusion Models (LDMs), Stable Diffusion, Noise schedules, ControlNet.
* 🛠️ **Hands-on Project**: `02_dcgan_synthetic_image_generation.ipynb`

---

### 🔹 Module 3: Transformer Architectures & Core LLM Mechanics
* **Attention Mechanisms**:
  * Scaled Dot-Product Attention, Multi-Head Self-Attention, Positional Encoding.
* **Transformer Archetypes**:
  * Encoder-Only (BERT) | Decoder-Only (GPT series) | Encoder-Decoder (T5).
* **LLM Architecture Evolution**:
  * Context window expansion, RoPE (Rotary Position Embeddings), KV-Caching.
* **Prompt Engineering & Optimization**:
  * System Prompts, Zero-Shot / Few-Shot Learning.
  * Chain-of-Thought (CoT), Tree-of-Thought (ToT), Directional Stimulus Prompting.
* 🛠️ **Hands-on Project**: `03_structured_prompt_chaining_api.py`

---

### 🔹 Module 4: Open-Source Models & Hugging Face Ecosystem
* **Hugging Face Hub**: Model Hub navigation, Dataset Loading, `transformers` library pipelines.
* **Open-Source LLMs**: Working with Llama-3, Mistral, Qwen, and Phi models.
* **Developer Tools & Coding Assistants**: Integrating GitHub Copilot, OpenAI Codex, and Tabnine into workflows.
* **Model Quantization Concepts**:
  * Precision formats: FP32, FP16, INT8, INT4.
  * Quantization formats: GGUF, AWQ, GPTQ for local execution.
* 🛠️ **Hands-on Project**: `04_huggingface_text_summarizer.ipynb`

---

### 🔹 Module 5: Parameter-Efficient Fine-Tuning (PEFT)
* **Fine-Tuning Methodologies**: Full Fine-Tuning vs. Parameter-Efficient Fine-Tuning.
* **Low-Rank Adaptation (LoRA)**:
  * Rank matrices ($A$ and $B$), trainable parameter reduction, merging weights.
* **Quantized LoRA (QLoRA)**:
  * 4-bit NormalFloat (NF4), Double Quantization, Paged Optimizers.
* **Supervised Fine-Tuning (SFT)**: Dataset preparation, Alpaca format, TRL (`SFTTrainer`).
* 🛠️ **Hands-on Project**: `05_qlora_llama3_finetuning.ipynb`

---

### 🔹 Module 6: Embeddings, Vector Databases & RAG Architecture
* **Semantic Embeddings**: Vector representation, Cosine Similarity, Euclidean Distance, Dot Product.
* **Vector Databases**: Setting up, indexing, and querying ChromaDB, FAISS, Pinecone, or Qdrant.
* **Retrieval-Augmented Generation (RAG)**:
  * Naive RAG: Document loading, Chunking strategies (Fixed-size, Semantic), Embedding, Storage, Retrieval.
  * Advanced RAG: Hybrid Search (BM25 + Dense Vector), Re-ranking (Cohere Rerank), Context Compression.
* 🛠️ **Hands-on Project**: `06_rag_pdf_assistant.py`

---

### 🔹 Module 7: Orchestration Frameworks & Autonomous AI Agents
* **LangChain Framework**:
  * LCEL (LangChain Expression Language), Prompts, Models, Output Parsers.
  * Memory types (Buffer, Conversation Summary), Chains (Sequential, Router).
* **LlamaIndex**: Data Ingestion, Document Stores, Indexing strategies.
* **Autonomous AI Agents**:
  * ReAct Framework (Reason + Act).
  * Multi-Agent Systems: LangGraph, CrewAI, AutoGen for multi-step tasks.
* 🛠️ **Hands-on Project**: `07_multi_agent_researcher.py`

---

### 🔹 Module 8: LLM Evaluation, Observability & Guardrails
* **Evaluation Frameworks**:
  * Measuring RAG performance using **Ragas** (Faithfulness, Answer Relevance, Context Recall/Precision).
* **Observability & Tracing**:
  * Tracking token costs, latency, and execution traces using LangSmith or Phoenix.
* **AI Safety & Guardrails**:
  * Prompt Injection prevention, PII masking, Output filtering (NeMo Guardrails).
* 🛠️ **Hands-on Project**: `08_rag_evaluation_langsmith.py`

---

### 🔹 Module 9: Production MLOps & API Deployment
* **Model Serving**: Building production REST APIs using FastAPI.
* **High-Performance Serving Engines**: vLLM, Ollama, TensorRT-LLM setup.
* **Containerization**: Writing Dockerfiles, multi-stage builds, GPU enablement (`nvidia-docker`).
* **Frontend Interfaces**: Building quick demo UIs with Streamlit or Gradio.
* 🛠️ **Hands-on Project**: `09_dockerized_rag_fastapi_app/`

---

### 🔹 Module 10: Capstone Enterprise Applications
* **Financial Report Synthesizer**: Automated extraction, summarization, and trend detection from raw financial statements using LangChain and Hugging Face.
* **Smart Hiring Tool**: Parsing resumes, automated profile matching against job requirements, and candidate evaluation using RAG and Agentic workflows.
* 🛠️ **Hands-on Project**: `10_capstone_enterprise_solution/`

---

## 🛠️ Tech Stack & Tools Used

* **Languages**: Python 3.10+
* **Frameworks**: PyTorch, TensorFlow, Hugging Face `transformers`, `peft`, `trl`
* **Orchestration**: LangChain, LangGraph, LlamaIndex, CrewAI
* **Vector Databases**: ChromaDB, FAISS
* **Deployment & Ops**: FastAPI, Docker, Streamlit, LangSmith
* **APIs**: OpenAI, Groq, Hugging Face Inference API

---

## 📁 Suggested Repository Directory Structure

```text
.
├── 01_deep_learning_foundations/
│   └── cnn_classifier.ipynb
├── 02_generative_vision/
│   └── dcgan_mnist.ipynb
├── 03_transformers_and_prompting/
│   └── structured_prompts.py
├── 04_huggingface_ecosystem/
│   └── hf_pipelines.ipynb
├── 05_peft_and_finetuning/
│   └── qlora_finetune.ipynb
├── 06_vector_dbs_and_rag/
│   └── pdf_rag_assistant.py
├── 07_agents_and_orchestration/
│   └── multi_agent_workflow.py
├── 08_eval_and_observability/
│   └── ragas_evaluation.py
├── 09_deployment_and_mlops/
│   ├── app/
│   │   ├── main.py
│   │   └── Dockerfile
│   └── docker-compose.yml
├── 10_capstone_projects/
│   └── financial_report_generator/
├── requirements.txt
└── README.md
