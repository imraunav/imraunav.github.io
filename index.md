---
layout: home
title: About
---

# Hi, I'm Raunav

I'm a computer vision and machine learning engineer focused on **representation learning**, **signal processing**, and **first-principles machine learning**. Currently working on driver behavior modeling from trajectories and video perception at scale.

[GitHub](https://github.com/imraunav) · [LinkedIn](https://linkedin.com/in/raunav) · [Email](mailto:raunavghosh@gmail.com)

---

## Experience

### Senior Engineer — Bosch Global Software Technologies
*December 2025 – Present*
* **Self-Supervised Trajectory Representation:** Designed self-supervised learning backbones leveraging DINO-style self-distillation and contrastive objectives to model joint ego- and surrounding-agent spatio-temporal dynamics.
* **Transformer-Based Kinematic Architecture:** Implemented a pure Transformer backbone with Rotary Position Embeddings (RoPE) to encode multi-agent kinematic and positional state sequences across discrete timesteps into compact scenario embeddings.
* **Large-Scale Scenario Mining & Retrieval:** Built embedding-based retrieval pipelines to query across ~10,000 hours of unlabelled driving logs, evaluating scenario discovery using Recall@25 across safety-critical maneuvers (e.g., aggressive cut-ins, hard braking, lane changes, and unprotected turns).
* **Automated Curation for Downstream AI:** Structured embedding spaces that interface with vector indexing (Qdrant) to curate targeted corner-case datasets, feeding downstream behavioral prediction and Vision-Language-Action (VLA) modeling pipelines.
* **Multimodal Perception (In Progress):** Developing video-based representation learning to enable cross-modal retrieval aligning temporal trajectories with visual scene dynamics.

### Computer Vision Engineer — Vehant Technologies Pvt Ltd.
*June 2024 – November 2025*
* **Streaming Image Quality Enhancement:** Designed and deployed low-latency ISP algorithms tailored to real-time baggage line-scan detectors:
  * Adapted CLAHE for streaming line-scan data operating on 16-scanline sliding buffers, resolving spatial boundary artifacts and ensuring neighborhood photometric consistency across frames.
  * Implemented edge-enhancement and high-frequency sharpening routines to preserve fine structural contours of complex, overlapping items.
  * Developed deep-learning super-resolution models (leveraging EDSR and GAN-based architectures) to recover 4x high-frequency spatial details beyond physical sensor resolution limits.
* **Dual-Energy Material Discrimination:** Formulated algorithms leveraging high- and low-energy X-ray absorption profiles to discriminate material composition, providing physical material cues alongside geometric shapes for downstream threat identification.

---

## Education

### Indian Institute of Technology (IIT) Mandi
*M.Tech in Communication and Signal Processing (Machine Learning Specialization)*  
*August 2022 – May 2024*

#### Honors
* *Outstanding Academic Achievement Award*
* *Vehant Research Fellowship*

### University of Engineering and Management (UEM), Kolkata
*B.Tech in Electronics and Communications Engineering*  
*August 2017 – May 2021*

---

<!-- ## Key Projects

* **[Project Name](https://github.com/...):** Implemented [architecture/algorithm] from scratch in PyTorch/C++; benchmarked on [Dataset].
* **[Technical Writeup Title](/posts/topic):** A breakdown of trade-offs in [technical topic].

--- -->

## Technical Toolkit
* **Languages:** Python, C++, Bash
* **Core:** PyTorch, OpenCV, Git, Linux