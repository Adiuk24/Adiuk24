# 👋 Hi, I'm Arif Ahmed Adito (@Adiuk24)

Independent AI Researcher · Founder, Adioris Tech · Head of Business @ Tapmad · EMBA, North South University

---

## 🧠 Research

### Training a Language Model End-to-End in Rust: An Experience Report

> *The dominant failure mode outside the PyTorch/CUDA ecosystem is not a crash — it's a run that learns nothing while the loss curve falls smoothly.*

A from-scratch Rust pretraining project hit **eight silent defects across two ML frameworks** (Candle and Burn) — every one passed ordinary loss-curve inspection. The companion artifact, the **Gradient-Flow Arbiter**, is a framework-agnostic verification harness that catches them in seconds, before compute is spent: dead gradients, wrong fused backwards, no-effect positional encodings, and pathological data ordering. Every test ships positive *and* negative controls.

🔧 **Code** → [Adiuk24/gradient-flow-arbiter](https://github.com/Adiuk24/gradient-flow-arbiter) (MIT)

### Eyla: Toward an Identity-Anchored LLM Architecture with Integrated Biological Priors

> *Why do LLMs forget who they are the moment someone tries to manipulate them?*

I spent a year researching this question — without a lab, without a co-author, and without a programming background.

The result: a published paper on arXiv proposing a novel architecture for identity-consistent AI, introducing the **Identity Consistency Score (ICS)** benchmark, and honestly documenting what happens when a non-programmer attempts to build cutting-edge AI using only AI tools.

📄 **arXiv:2604.00009** → [arxiv.org/abs/2604.00009](https://arxiv.org/abs/2604.00009)  
🤗 **Hugging Face** → [huggingface.co/Adiuk](https://huggingface.co/Adiuk)

**Key contributions:**
- Identity-anchored fine-tuning via "Soul Pass" training
- HiPPO-initialized State-Space Models for biologically-inspired memory
- Identity Consistency Score (ICS) — a new benchmark measuring LLM resistance to manipulation
- First-person failure analysis: 5 systematic failure modes of AI-assisted development

---

## 🚀 What I Build

### 🤖 Eyla AIOS
A local-first agentic AI operating system for Bangladeshi students — runs on consumer hardware (8–16GB RAM), no cloud dependency, no subscription cost. Sovereign AI for underserved markets. Fine-tuned tool-calling models are public on Hugging Face.

→ [huggingface.co/Adiuk](https://huggingface.co/Adiuk)

### 🎬 Tapmad Anti-Piracy Platform
Production-ready OTT content protection system for live streaming environments.

→ [Adiuk24/tapmad-anti-piracy](https://github.com/Adiuk24/tapmad-anti-piracy)

---

## 🛠 Stack & Tools

`Python` · `Rust` · `TypeScript` · `Ollama` · `Qwen3-8B` · `SQLite` · `Tauri v2` · `FastAPI` · `Docker` · `AWS`

---

## 📫 Connect

- 🌐 [arifadito.com](https://arifadito.com)
- 🤗 [huggingface.co/Adiuk](https://huggingface.co/Adiuk)
- 💼 [LinkedIn](https://www.linkedin.com/in/arif-adito-025088b4)
- 📄 [arXiv Paper](https://arxiv.org/abs/2604.00009)

---

*Building AI that knows who it is — from Dhaka, Bangladesh 🇧🇩*
