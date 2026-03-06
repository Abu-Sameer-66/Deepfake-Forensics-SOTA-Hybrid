<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&ColorList=00ffcc,0575e6,00f260,38ef7d&height=230&section=header&text=DEEPFAKE%20FORENSICS&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=SOTA%20Hybrid%20Transformer-CNN%20Pipeline&descAlignY=60&descAlign=50" width="100%"/>
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=26&pause=900&color=ffffff&center=true&vCenter=true&width=900&lines=Enterprise-Grade+Deepfake+Detection;Hybrid+Transformer-CNN+Backbone;Explainable+AI+(XAI)+Integrated;99.92%+Precision+Forensic+Results" />
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Precision-99.92%25-00ffcc?style=for-the-badge&logo=target&logoColor=black" />
  <img src="https://img.shields.io/badge/Accuracy-98.50%25-white?style=for-the-badge&logo=checkmarx&logoColor=black" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-0575e6?style=for-the-badge" />
</p>

---

## 🛡️ Project Vision: The Forensic Guard

> **Deepfake Forensics** is a high-precision security engine designed to detect GAN and Diffusion-based artifacts. By fusing **ResNet-18** (local features) with **Transformer Encoders** (global context), we eliminate the "blind spots" found in traditional CNNs.

### ⚡ Engineering Highlights
- **Hybrid Architecture:** Dual-path feature fusion for microscopic artifact detection.
- **Explainable AI:** Integrated Grad-CAM for visual forensic proof.
- **Production Grade:** Optimized for Dual Tesla T4 GPUs with Automatic Mixed Precision (AMP).
- **Large-Scale:** Trained on 140,000+ high-resolution clinical and facial samples.

---

## 🧪 The Ablation Matrix
Every architectural decision was empirically validated through a 5-stage ablation study.

| Stage | Architecture | Accuracy | Precision | Status |
| :--- | :--- | :--- | :--- | :--- |
| 01 | ANN Baseline | 87.18% | 87.40% | ❌ Spatial Info Loss |
| 02 | Vanilla CNN | 67.92% | 60.97% | ❌ Model Collapse |
| 03 | HAM (Attention) | 85.53% | 81.95% | ⚠️ Context Bottleneck |
| 04 | Vision Transformer | 98.32% | 97.02% | ✅ High Performance |
| **05** | **SOTA Hybrid** | **98.50%** | **99.92%** | **🏆 OPTIMIZED** |

---

## 🔍 Explainable AI (XAI)
Forensics is useless without proof. Our model utilizes **Grad-CAM** to highlight exactly where the AI-generator failed.



> **Insight:** The system focuses on **periorbital asymmetry** and **hair-to-skin transitions**, areas where generative models typically struggle with mathematical consistency.

---

## 🏗️ System Architecture

```text
Input Image (224x224)
   │
   ├── CNN Stream (ResNet-18 Backbone) ──▶ Local Texture Artifacts
   │                                            │
   ├── Transformer Stream (Encoder)    ──▶ Global Structural Gaps
   │                                            │
   └── Feature Fusion Layer (Multi-Head) ───────┘
             │
             └── Prediction: [Real | Fake] (99.92% Precision)
