<h1 align="center">Ammar Hassona</h1>
<p align="center">AI/ML Engineer</p>

---

I'm an AI/ML engineer working across LLM post-training, speech AI, and ML infrastructure. I fine-tune and align language models using SFT, DPO, and LoRA, build the training pipelines around them, and have worked on Arabic speech systems including TTS, ASR, and speaker diarization. Right now I'm learning GPU kernel programming and lower-level systems.

I'm an open-source contributor to Hugging Face TRL and pandas, and co-authored the [EGY-MER dataset paper](https://doi.org/10.1007/s10579-026-09941-9), published in Language Resources and Evaluation (Springer, 2026).

## Open Source

| Contribution | Repo |
|---|---|
| Fixed an AsyncGRPO checkpoint-resume bug that caused unnecessary vLLM inference on restart. Added rollout-state persistence and dataset fast-forwarding so resumes pick up exactly where training stopped | [huggingface/trl #5911](https://github.com/huggingface/trl/pull/5911) |
| Fixed `read_csv(engine="pyarrow")` silently ignoring `encoding_errors` for bytes input. It now raises a clear unsupported-option error instead of returning wrong results or a misleading `UnicodeDecodeError` | [pandas-dev/pandas #71377](https://github.com/pandas-dev/pandas/pull/71377) |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![W&B](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

---

## Projects

| Project | Description |
|---|---|
| [Speculative Decoding from Scratch](https://github.com/AmmarHassona/speculative-decoding-from-scratch) | PyTorch impl of Leviathan et al. 2022 with acceptance rate benchmarks across model pairs |
| [trainsafe](https://github.com/AmmarHassona/trainsafe) | HuggingFace/TRL callback for behavioral health checks during fine-tuning. Catches language drift, output collapse, and repetition loops mid-training |
| [LLM Cache Proxy](https://github.com/AmmarHassona/llm_cache_proxy) | Rust caching proxy for LLM APIs, 4ms cached vs 2.2s live, ~48% cost reduction |
| [ML Inference Platform](https://github.com/AmmarHassona/ml-inference-platform) | ONNX serving with canary routing, shadow mode, drift detection, and Grafana observability |
| [clamp-cc](https://github.com/AmmarHassona/clamp-cc) | Terminal UI for fine-grained Claude Code context compaction. Tag individual turns, then generate targeted /compact instructions |
| [TEN-VAD Realtime](https://github.com/AmmarHassona/ten-vad-realtime) | Real-time speech segmentation with WebSocket event streaming built on TenVAD |
