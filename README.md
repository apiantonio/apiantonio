<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=2F81F7&center=true&vCenter=true&width=750&lines=Hi%2C+I'm+Antonio+Apicella+%F0%9F%91%8B;AI+Engineer+%7C+LLM+%26+Agentic+RAG+Systems;Generative+AI+%7C+Computer+Vision;Building+intelligent+systems+that+work+in+production" alt="Typing SVG" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio~apicella/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:apiantonio.aa@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/apiantonio?style=for-the-badge&logo=github&labelColor=161b22&color=2f81f7)](https://github.com/apiantonio?tab=followers)

</div>

---

## 👨‍💻 About Me

I'm an **AI Engineer** and **MSc student in Computer Engineering** at the University of Salerno, specializing in Artificial Intelligence. I design and build end-to-end intelligent systems — from production-grade **Agentic RAG pipelines** and **LLM applications** to state-of-the-art **Computer Vision** and **Generative AI** architectures.

My software engineering background means I don't just prototype — I build systems that are **modular, maintainable, and ready for real-world deployment**.

- 🔭 &nbsp;Focus areas: **Agentic LLM Systems · Generative AI · Real-time Computer Vision**
- 🎓 &nbsp;MSc in Computer Engineering (AI) @ **University of Salerno** — graduating 2025/26
- 🌍 &nbsp;Based in **Campania, Italy** · Open to relocation / remote
- 📬 &nbsp;Reach me: **apiantonio.aa@gmail.com**

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [DIEM Agentic RAG Chatbot](https://github.com/apiantonio/LLM_powered_chatbot_DIEM)

**Production-grade LLM system** for the DIEM Department at the University of Salerno.

An intelligent assistant that autonomously queries multiple vector store collections, rewrites ambiguous queries, and generates grounded multilingual answers — with full guardrail and RAGAS evaluation pipelines.

**Highlights:**
- Agentic parallel tool-calling (LangChain) — LLM autonomously selects knowledge collections
- Multi-threaded BFS web crawler feeding 3 ChromaDB collections
- Smart conversational memory with semantic filtering
- 3-stage Llama 3.3 70B guardrail system (injection · toxicity · hallucination)
- Full RAGAS evaluation pipeline → JSON/CSV/Excel reports

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
<td width="50%" valign="top">

### ⚽ [SoccerNet Player Tracking](https://github.com/apiantonio/SoccerNet-tracking_AV2025-26)

**Computer Vision pipeline** for the SoccerNet Benchmark — A.Y. 2025/26 @ UniSa.

Full Tracking-by-Detection system combining high-recall detection with motion-based tracking and semantic field masking.

**Results on Official Test Set:**
| Metric | Score |
|--------|-------|
| 🏆 HOTA | **0.742** |
| DetA | 0.863 |
| AssA | 0.636 |
| PTBS | 1.527 |

- YOLOv11x at 1088px with adaptive HSV/LAB field masking
- BoT-SORT with Sparse Optical Flow (GMC) — no visual Re-ID needed
- Modular YAML-configurable pipeline (tracking · behaviour · eval · viz)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv11-00FFFF?style=flat-square&logo=ultralytics&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 [Attribute-Guided Face Generation](https://github.com/apiantonio/Attribute-Guided-Face-Generation-A-Mamba-Diffusion-and-VAE-Framework)

**Generative AI research** comparing three architectures for conditional face synthesis on CelebA.

A comparative framework for controlled face generation (gender · expression · age) benchmarking three distinct generative paradigms.

**Architectures implemented:**
- **Vision Mamba (SSM)** — custom autoregressive implementation with parallel scan (pscan)
- **Conditional DDPM** — U-Net with sinusoidal time encoding + Classifier-Free Guidance
- **Conditional VAE** — symmetric encoder-decoder with residual skip connections

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FDEE21?style=flat-square&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

</td>
<td width="50%" valign="top">

### 🛰️ [Rural Image Segmentation On-Board](https://github.com/apiantonio/Rural-Images-Segmentation-on-board)

**Semantic segmentation** optimized for resource-constrained on-board deployment.

Semantic segmentation of rural aerial imagery using a ResNet18 encoder coupled with a U-Net decoder architecture, designed for efficient inference on embedded hardware.

**Key aspects:**
- ResNet18 pretrained backbone with U-Net skip-connection decoder
- Optimized for on-board inference (low memory footprint)
- End-to-end pipeline in PyTorch with Jupyter-based experimentation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Core Tech Stack

### 🤖 AI · LLM · Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FDEE21?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### 👁️ Computer Vision
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics_YOLO-00FFFF?style=for-the-badge&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### 🗄️ Vector Stores & LLM Infra
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### ⚙️ Engineering & DevOps
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="github-metrics.svg" alt="Antonio's GitHub Metrics" width="500"/>
</div>

---

## 📫 Let's Connect

<div align="center">

I'm actively looking for **AI Engineer** / **ML Engineer** opportunities (full-time or stage).
If you're working on something interesting in the LLM, GenAI, or Computer Vision space — let's talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-antonio~apicella-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio~apicella/)
[![Email](https://img.shields.io/badge/Email-apiantonio.aa@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:apiantonio.aa@gmail.com)

</div>
