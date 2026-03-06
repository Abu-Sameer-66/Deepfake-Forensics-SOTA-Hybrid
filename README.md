# <p align="center"> DEEPFAKE FORENSICS: SOTA HYBRID PIPELINE</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=glitch&text=Deepfake%20Forensics%20SOTA&fontSize=60&color=00ffcc&background=000000&animation=twinkling" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Precision-99.92%25-00ffcc?style=for-the-badge&logo=target" />
  <img src="https://img.shields.io/badge/Accuracy-98.50%25-white?style=for-the-badge&logo=checkmarx" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
</p>

---

## 🌌 Project Vision
Detecting hyper-realistic AI-generated content requires more than just standard convolutions. This repository implements a **Hybrid Transformer-CNN** architecture designed to hunt for microscopic forensic artifacts in 140,000+ high-resolution images.

### ⚡ Feature Highlights:
* **Hybrid Backbone:** CNN (ResNet18) for local texture + Transformer for global structure.
* **XAI Powered:** Grad-CAM integration for interpretability.
* **Precision Focused:** Specifically engineered to minimize False Positives (99.92% Precision).

---

## 🧪 The Ablation Matrix
We didn't just build a model; we conducted an evolutionary audit.

| Stage | Architecture | Accuracy | Precision | Status |
| :--- | :--- | :--- | :--- | :--- |
| 01 | ANN Baseline | 87.18% | 87.40% | ❌ Spatial Loss |
| 02 | Vanilla CNN | 67.92% | 60.97% | ❌ Model Collapse |
| 03 | HAM (Attention) | 85.53% | 81.95% | ⚠️ Limited Context |
| 04 | Vision Transformer | 98.32% | 97.02% | ✅ High Performance |
| **05** | **SOTA Hybrid** | **98.50%** | **99.92%** | **🏆 OPTIMIZED** |

---

## 🔍 Explainable AI: Grad-CAM Visualization
Forensics is about proof. Below is how our model "sees" the fake:
> *The heatmaps indicate a high focus on the **periorbital region** and **hair-to-skin transitions**, where GANs typically struggle with boundary consistency.*

<p align="center">
  <img src="https://img.shields.io/badge/Status-XAI_Active-00ffcc?style=flat-square" />
</p>

---

## 🛠️ Technical Stack
```yaml
Framework: PyTorch 2.x
Hardware: Dual Tesla T4 (AMP Enabled)
Optimizer: AdamW + Cosine Annealing
Data: 140K Samples (Forensic Grade)

## 🌌 Overview
In the era of hyper-realistic generative AI, traditional forensic methods are failing. This repository presents a **State-of-the-Art (SOTA) Deepfake Detection Pipeline**. By fusing the local feature extraction of **ResNet-18** with the global self-attention of a **Transformer Encoder**, we achieve a precision-heavy model capable of identifying GAN and Diffusion-based artifacts.


## 🚀 Technical Implementation
* **Hardware:** Optimized for Dual Tesla T4 GPUs using `DataParallel`.
* **Optimization:** Automatic Mixed Precision (AMP) for 2x faster training.
* **Scheduler:** Cosine Annealing with Restarts for superior convergence.
* **Pipeline:** Modular PyTorch code for easy adaptation to new datasets.

---

## 📂 Repository Structure
```text
├── notebooks/      # Full training & evaluation pipeline
├── results/        # CSV metrics and performance logs
├── visuals/        # Grad-CAM Heatmaps & Confusion Matrices
└── README.md       # Analysis & Documentation
