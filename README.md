# Physics Is All You Need: Solar Forecasting Visualizer ☀️🧠

[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
![WebGL](https://img.shields.io/badge/Built%20With-WebGL-red)
![Status](https://img.shields.io/badge/Status-Preprint-orange)

### 🚀 [Click Here to Try the Live 3D Simulation](https://Marco9249.github.io/Physics-Informed-Solar-Vis/)

---

## 📄 Research Paper

**Title:** *Physics Is All You Need: Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting*

We recommend reading the full preprint on **IEEE TechRxiv** to get the latest version and citation metrics:

[![Read on TechRxiv](https://img.shields.io/badge/Read%20Paper-IEEE%20TechRxiv-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://www.techrxiv.org/1376729)

> **Abstract:** Accurate Global Horizontal Irradiance (GHI) forecasting is a prerequisite for grid stability. This paper challenges the prevailing "complexity-first" paradigm by proposing a lightweight, Physics-Informed Hybrid CNN-BiLSTM framework. The proposed methodology integrates a Convolutional Neural Network (CNN) for feature extraction with a Bi-Directional LSTM for temporal dependency learning, guided by explicit physical knowledge.

---

## 🎥 About the Visualization

This tool visualizes the **1D-Convolutional** sliding window mechanism described in the paper.
- **Teal Grid:** Represents the multivariate input tensor (24 Time Steps x 15 Physics Features).
- **Yellow Box:** Represents the Kernel (Size 3) performing feature extraction across time.
- **Goal:** To demonstrate how the model captures "local patterns" (like cloud transients) while respecting physical constraints.

---

## ❞ Citation

If you find this code or the paper useful, please cite our work:

```bibtex
@article{Abdullah2026Physics,
  title={Physics Is All You Need: Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting},
  author={Mohammed Ezzaldin Babiker Abdullah, Rufaidah Abdallah Ibrahim Mohammed},
  journal={IEEE TechRxiv},
  year={2026}
}
