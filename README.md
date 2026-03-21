# Srini Ananthakrishnan

**Creator, OpenObscure** · Director of Data Security & AI Privacy @ CNA Insurance · 25+ years in distributed systems, AI/ML, and privacy engineering

---

## 🔐 Active Project — OpenObscure

> **On-device privacy firewall for AI agents** — intercepts LLM prompts and responses in real time, encrypts PII with FF1 Format-Preserving Encryption, and scans every LLM response for manipulation via a cognitive firewall. Zero cloud dependency. Designed for Enchanted, RikkaHub, and any OpenAI-compatible AI agent.

[![OpenObscure](https://img.shields.io/badge/OpenObscure-Privacy%20Firewall%20for%20AI%20Agents-1a2d5a?style=for-the-badge)](https://github.com/srianant/openobscure)

### Architecture at a glance

| Layer | Component | Purpose |
|---|---|---|
| Detection | TinyBERT-4L-312D INT8 + CRF | Named entity recognition, low-latency on-device |
| Encryption | FF1 Format-Preserving Encryption | Reversible token substitution, structure-safe |
| Cognitive Firewall | TinyBERT cascade · 250-phrase dictionary | Scans every LLM response for manipulation — EU AI Act Article 5 |
| Vision | BlazeFace + SCRFD | Face solid-fill redaction before LLM upload |
| OCR | PaddleOCR via ONNX Runtime | Text extraction from images, PII interception |
| Safety | 5-class ViT NSFW classifier | Content classification pre-transmission |

**Deployment tiers:** Lite · Standard · Full — within a **275 MB RAM / 70 MB storage** budget.

**Integrations:** [Enchanted](https://github.com/nicepkg/enchanted) (iOS) · [RikkaHub](https://github.com/rikkahub/rikkahub) (Android) · [OpenClaw](https://github.com/openclaw/openclaw) (Gateway Agent)

**Compliance:** EAR/TSU notified · EU AI Act Article 5 reviewed · Export Control Notice included

📄 [Read the launch article](https://medium.com/@srini.anant/your-ai-agent-is-leaking-your-data-we-built-a-privacy-firewall-to-stop-it-cc5ea27d2589) · 🌐 [Landing page](https://github.com/openobscure/openobscure)

---

## 🗂️ Legacy Research Projects

These repositories represent earlier applied ML and computer vision research. They are no longer actively maintained but remain publicly available as reference implementations.

| Repository | Domain | Stack | Notes |
|---|---|---|---|
| [**computer_vision**](https://github.com/srianant/computer_vision) | Computer Vision | C/C++, Python, OpenPose, DLIB, Keras, TensorFlow | Object detection, tracking, face recognition, gesture & emotion recognition |
| [**DNN_Hyperparameter_Optimization**](https://github.com/srianant/DNN_Hyperparameter_Optimization) | AutoML / Distributed ML | Python, Distributed TensorFlow | Neural network hyperparameter optimization via random search over distributed PS/Worker architecture |
| [**kalman_filter_multi_object_tracking**](https://github.com/srianant/kalman_filter_multi_object_tracking) | Computer Vision | Python, OpenCV | Multi-object tracking using Kalman filter estimation |
| [**image_compression**](https://github.com/srianant/image_compression) | Numerical Methods | Python, Jupyter | Image compression via SVD, QR, and LU decomposition |

> **Note:** These projects were built against TensorFlow 1.x / Keras 2.x era tooling. APIs and dependencies may be outdated.

---

## Background

- **Current:** Creator, OpenObscure · Director, Data Security & AI Privacy — CNA Insurance
- **Focus areas:** AI privacy engineering · LLM security · On-Device ML · Cognitive Firewall Research · Privacy-Preserving Systems
- **Earlier work:** Embedded systems, Distributed ML infrastructure, Computer Vision

---

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white"/>
</p>
