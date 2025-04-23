# 🧠 AI-Doctor

AI-Doctor is a medical reasoning assistant powered by the **DeepSeek-R1 Distill LLaMA 8B** model. Fine-tuned using **Unsloth** and medical chain-of-thought (CoT) datasets, AI-Doctor delivers clinical-grade answers with logical reasoning.

This project is part of a larger vision to unify multiple medical AI tools into a single app.

---

## 🚀 Features

- Clinical question-answering using state-of-the-art LLM
- Chain-of-thought reasoning for better interpretability
- Fine-tuned on a curated medical dataset (`FreedomIntelligence/medical-o1-reasoning-SFT`)
- Lightweight deployment using 4-bit quantization and PEFT (LoRA)

---

## 🧩 Tech Stack

- [DeepSeek-R1 Distill LLaMA 8B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-8B)
- [Unsloth](https://github.com/unslothai/unsloth) for optimized LLM training
- 🤗 Transformers & PEFT
- Python, Torch, Gradio (for frontend integration)
- Colab/GPU-friendly

---
