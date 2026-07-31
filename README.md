<h1 align="center">Ammar Hassona</h1>
<p align="center">AI/ML Engineer</p>

---

I build production ML systems, from fine-tuning open-source LLMs to deploying inference infrastructure. Fine-tuned and aligned open-source SLMs on Arabic conversational data using SFT, DPO, and LoRA, with training pipelines and experiments tracked on W&B. Previously built speech processing, TTS, and STT systems for Arabic audio at production scale.

Co-authored the [EGY-MER dataset paper](https://www.researchsquare.com/article/rs-8006895/v1) — accepted in Language Resources and Evaluation (Springer, 2026) · preprint

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**ML & Training**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

SFT · DPO · LoRA · Instruction Tuning · Contrastive Pre-training · Multimodal ML

**MLOps & Infrastructure**

![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![W&B](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

---

## 📌 Projects

| Project | Description |
|---|---|
| [LLM Cache Proxy](https://github.com/AmmarHassona/llm_cache_proxy) | Rust caching proxy for LLM APIs — 4ms cached vs 2.2s live, ~48% cost reduction |
| [ML Inference Platform](https://github.com/AmmarHassona/ml-inference-platform) | ONNX serving with canary routing, shadow mode, drift detection, and Grafana observability |
| [trainsafe](https://github.com/AmmarHassona/trainsafe) | HuggingFace/TRL callback for behavioral health checks during fine-tuning — catches language drift, output collapse, repetition loops mid-training |
| [Speculative Decoding from Scratch](https://github.com/AmmarHassona/speculative-decoding-from-scratch) | PyTorch impl of Leviathan et al. 2022 with acceptance rate benchmarks across model pairs |
| [clamp-cc](https://github.com/AmmarHassona/clamp-cc) | TUI for fine-grained Claude Code context compaction — tag turns, generate targeted instructions |
| [TEN-VAD Realtime](https://github.com/AmmarHassona/ten-vad-realtime) | Real-time speech segmentation with WebSocket event streaming built on TenVAD |
| [Orbis](https://github.com/AmmarHassona/orbis) | Full-stack AI chatbot with RAG, web search, and streaming chat — Next.js + FastAPI + Groq |
