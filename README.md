### Hi there, I'm Nikita 👋
#### ML Research Engineer | Deep Learning Architect

I specialize in **designing custom neural architectures** for NLP and Computer Vision. My focus is solving "unsolvable" problems: **infinite context** in RAG, **high-performance inference** for heavy models, and **volumetric segmentation** on consumer hardware.

Currently an **Undergraduate Researcher at AI Lab**, bridging the gap between academic papers and production-grade software.

---

### 🛠 Tech Stack

**Deep Learning & Research**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![WandB](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

**LLM & NLP**
![RAG](https://img.shields.io/badge/RAG-Architecture-blue?style=flat-square)
![LoRA](https://img.shields.io/badge/PEFT%20%2F%20QLoRA-Fine--Tuning-green?style=flat-square)
![Longformer](https://img.shields.io/badge/Longformer-Context-orange?style=flat-square)

**Engineering & DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![AsyncIO](https://img.shields.io/badge/Python-AsyncIO-yellow?style=flat-square&logo=python&logoColor=white)

---

### 🚀 Featured Research & Projects

#### 🧠 [KOTODEX: Semantic Search Engine](https://github.com/Nikita-Podlutsky/reader-on-steroids)
A state-of-the-art RAG system designed for **long-context legal & scientific documents**.
*   **Problem:** Standard Bi-Encoders (SBERT) fail to capture context in 50+ page documents.
*   **Solution:** Implemented a **Hybrid Ranker** using **Longformer (4096 tokens)** with **Conditional Embeddings** (Document vector shifts based on Query).
*   **Performance:** Achieved **+17.7% Hit@1** accuracy vs. SBERT baseline.
*   **Engineering:** Optimized inference latency to **~250ms** via pre-computation and Sliding Window Attention.
*   **Stack:** *PyTorch, QLoRA, Docker, FastAPI, React (Knowledge Graph UI).*

#### 🩺 [3D-MoE-Seg: Volumetric Medical Segmentation](https://github.com/Nikita-Podlutsky/REPO-NAME)
Custom **3D U-Net** architecture with **Mixture-of-Experts (MoE)** blocks for MRI/CT analysis.
*   **Innovation:** Replaced standard convolutions with Dense MoE layers for dynamic feature selection.
*   **Optimization:** Implemented **Sliding Window Inference** with internal overlap handling to process high-res 3D volumes on consumer GPUs (avoiding OOM).
*   **Stack:** *PyTorch, Hydra, 3D-UNet, Medical Data.*

#### 🎙️ [DyWinT: Dynamic Window Transformer](https://github.com/Nikita-Podlutsky/REPO-NAME)
Streaming ASR architecture based on Conformer.
*   **Core Logic:** Internal windowing mechanism slicing audio within the model's `forward` pass.
*   **Feature:** Global Positional Encoding applied before slicing to preserve temporal context across windows.

---

### 📊 Github Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Nikita-Podlutsky&show_icons=true&theme=radical)
![Github Stats](https://github-readme-stats.vercel.app/api?username=Nikita-Podlutsky&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=f0f6fc&text_color=c9d1d9)
![Github top-langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Nikita-Podlutsky&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

---

### 📬 Contact

I am open to **R&D / ML Engineer** roles where I can apply deep architectural knowledge to solve production challenges.

[LinkedIn](https://linkedin.com/in/your-profile) • [Telegram](https://t.me/allscript)
