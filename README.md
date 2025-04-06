# SAiDL Spring 2025 Induction Assignment

Welcome! This repository contains my submission for the **SAiDL Spring 2025 Induction Assignment**. The assignment centered around two exciting and challenging tracks:

- **Core Machine Learning**
- **Diffusion Models**

It combined theory with hands-on implementation, encouraging deep exploration of modern machine learning techniques through experiments and evaluations.

---

## Author

**Name:** Soham Ulhas Pujari  
**ID:** 2024A7PS0490G

---

## Tracks Attempted

### 1. Core ML (Compulsory)

This track focused on **robust learning under noisy labels**. The goal was to test how different loss functions handle increasing levels of label noise:

- Introduced **symmetric noise** to the CIFAR-10 dataset.
- Implemented and compared:
  - `Cross-Entropy (CE)`
  - `Normalized Cross-Entropy (NCE)`
  - `Active-Passive Loss (APL = NCE + RCE)`
- Plotted accuracy vs. noise rate to highlight differences in **robustness**.
- Evaluated performance as noise levels increased.

### 2. Diffusion

This track explored the training and evaluation of **Transformer-based Diffusion Models (DiT)**:

- Analyzed how **Classifier-Free Guidance (CFG)** and **sampling steps** affect image quality.
- Integrated **Xformers attention** to improve sampling speed and memory usage.
- Trained DiT models with:
  - `Full Attention`
  - `Sliding Window Attention (SWA)`
- Evaluated generated samples using:
  - `Fréchet Inception Distance (FID)`
  - `CLIP Mean Maximum Discrepancy (CMMD)`
- Extended CMMD evaluation using different vision-language models:
  - `CLIP`
  - `SigLIP`
  - `ALIGN`
