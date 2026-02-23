<h1 align="center">👋 Hi, I'm Ammar</h1>
<p align="center">
  🧠 AI & Data Science • ⚙️ ML Engineering  
</p>

---

## 🚀 What I Do

I'm passionate about building production ML systems with a focus on **multimodal architectures**, **speech processing**, and **LLM infrastructure**:

- Design and train **multimodal fusion models** for emotion recognition and speech analysis
- Build **speech-processing pipelines** (TTS, STT, VAD, diarization) for Arabic and English
- Develop **LLM-powered tools** and semantic caching systems to optimize API costs
- Deploy **containerized ML systems** with Docker, FastAPI, and vector databases

---

## 🧰 Tech Stack

**Languages:** Python, Rust  
**ML/DL:** PyTorch, HuggingFace Transformers, Scikit-learn, PEFT (LoRA)  
**Speech & NLP:** Wav2Vec2, AraBERT, TTS/STT pipelines, VAD, Speaker Diarization  
**Infrastructure:** FastAPI, Docker, Redis, Qdrant, PostgreSQL  
**Tools:** Git, Linux, Weights & Biases, Jupyter

---

## 📌 Featured Work

### [MultiFusion-Core](https://github.com/AmmarHassona/multifusion-core)
🎓 **Bachelor's Thesis** – Multimodal emotion recognition for Egyptian Arabic
- Implemented and evaluated **5 fusion architectures** (early, late, hybrid, attention, transformer) achieving **61.84% test accuracy**
- Designed **semi-supervised pipeline** with contrastive pre-training on 5,000+ unlabeled samples
- Applied **LoRA** for parameter-efficient fine-tuning, reducing trainable parameters by 90%
- Built end-to-end pipeline: Arabic text preprocessing, audio/video feature extraction, training, evaluation

**Tech:** PyTorch, HuggingFace, AraBERT, Wav2Vec2, Swin Transformer, Weights & Biases

---

### [LLM Cache Proxy](https://github.com/AmmarHassona/llm_cache_proxy)
High-performance semantic caching proxy for LLM APIs
- **2-tier caching architecture**: Redis (exact match) + Qdrant (semantic similarity)
- Reduces API costs through intelligent response reuse and embedding-based retrieval
- Real-time **metrics dashboard** tracking cache hit rates, token usage, and cost savings
- Docker Compose deployment with health checks and monitoring

**Tech:** Rust (Axum, Tokio), Python (FastAPI), Redis, Qdrant, Docker

### [TEN-VAD Realtime](https://github.com/AmmarHassona/ten-vad-realtime)
Real-time speech segmentation and WebSocket event streaming built on TenVAD
- Extended TenVAD with **automatic speech segmentation** and a configurable silence/merge window
- Emits structured **WebSocket events** (`speech_start`, `segment_saved`, `merged`) for downstream integration
- Saves and merges raw WAV segments with full timestamp logging

**Tech:** Python, TenVAD, sounddevice, websockets

---

### Other Projects

**[IntelliTopic](https://github.com/AmmarHassona/IntelliTopic)** – Multi-modal topic generation platform powered by LLMs
