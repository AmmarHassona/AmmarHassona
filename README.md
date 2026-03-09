<h1 align="center">👋 Hi, I'm Ammar</h1>
<p align="center">
  🧠 AI & Data Science • ⚙️ ML Engineering  
</p>

## 🚀 What I Do

I'm passionate about building production ML systems with a focus on **multimodal architectures**, **speech processing**, and **LLM infrastructure**:

- Design and train **multimodal fusion models** for emotion recognition and speech analysis
- Build **speech-processing pipelines** (TTS, STT, VAD, diarization) for Arabic and English
- Develop **LLM-powered tools** and semantic caching systems to optimize API costs
- Deploy **containerized ML systems** with Docker, FastAPI, and vector databases
- Implement **LLM inference optimization** techniques from research papers (speculative decoding, caching)

---

## 🧰 Tech Stack

**Languages:** Python, Rust  
**ML/DL:** PyTorch, HuggingFace Transformers, Scikit-learn, PEFT (LoRA)  
**Speech & NLP:** Wav2Vec2, AraBERT, TTS/STT pipelines, VAD, Speaker Diarization  
**Infrastructure:** FastAPI, Docker, Redis, Qdrant, PostgreSQL, AWS (EC2, SageMaker, Lambda)
**Tools:** Git, Linux, Weights & Biases, Jupyter

---

## 📌 Featured Work

### [LLM Cache Proxy](https://github.com/AmmarHassona/llm_cache_proxy)
High-performance semantic caching proxy for LLM APIs
- **2-tier caching architecture**: Redis (exact match) + Qdrant (semantic similarity)
- Reduces API costs through intelligent response reuse and embedding-based retrieval
- Real-time **metrics dashboard** tracking cache hit rates, token usage, and cost savings
- Docker Compose deployment with health checks and monitoring

**Tech:** Rust (Axum, Tokio), Python (FastAPI), Redis, Qdrant, Docker

---

### [MultiFusion-Core](https://github.com/AmmarHassona/multifusion-core)
🎓 **Bachelor's Thesis** – Multimodal emotion recognition for Egyptian Arabic
- Implemented and evaluated **5 fusion architectures** (early, late, hybrid, attention, transformer) achieving **61.84% test accuracy**
- Designed **semi-supervised pipeline** with contrastive pre-training on 5,000+ unlabeled samples
- Applied **LoRA** for parameter-efficient fine-tuning, reducing trainable parameters by 90%
- Built end-to-end pipeline: Arabic text preprocessing, audio/video feature extraction, training, evaluation

**Tech:** PyTorch, HuggingFace, AraBERT, Wav2Vec2, Swin Transformer, Weights & Biases

---

### [Speculative Decoding from Scratch](https://github.com/AmmarHassona/speculative-decoding-from-scratch)
From-scratch implementation of speculative decoding based on Leviathan et al. (2022)
- Implemented probabilistic rejection sampling and residual resampling with no existing libraries
- Benchmarked across 3 model pairs and 4 prompt types — acceptance rates of 25–84% confirm correct implementation
- k ablation study shows theoretical optimum at k=4; back-of-envelope analysis projects 1.76–2.21x speedup at production-scale speed ratios

**Tech:** Python, PyTorch, HuggingFace Transformers

---

### [Orbis](https://github.com/AmmarHassona/orbis)                                                                                                   
Personal AI chatbot with RAG, web search, and multi-mode conversations
- Built full-stack app with **streaming chat** (SSE), **session management**, and 5 specialized modes (Health, Fitness, Mental, Study, General)      
- Implemented **RAG pipeline** with ChromaDB and HuggingFace embeddings — users upload documents (PDF, DOCX, TXT) as context                       
- Integrated **real-time web search** via Tavily API and profile-aware prompting using stored health data
- Designed REST API with FastAPI including auth, document management, analytics, and message search

**Tech:** Next.js, TypeScript, FastAPI, Groq (LLaMA 3.3), Supabase, ChromaDB, Tailwind CSS

---

### [TEN-VAD Realtime](https://github.com/AmmarHassona/ten-vad-realtime)
Real-time speech segmentation and WebSocket event streaming built on TenVAD
- Extended TenVAD with **automatic speech segmentation** and a configurable silence/merge window
- Emits structured **WebSocket events** (`speech_start`, `segment_saved`, `merged`) for downstream integration
- Saves and merges raw WAV segments with full timestamp logging

**Tech:** Python, TenVAD, sounddevice, websockets

---
