# [ICML 2026] WEVSR: Video Diffusion Generators for Real-World Video Super-Resolution with Wavelet-Enhanced VAE Encoder


**Authors:** Yuying Chen, Zhirui Liu, Linyan Jiang, Qifan Gao, Xianguo Zhang, Jianhou Gan, Wenqi Ren  
**Institutions:** Guangdong Laboratory of Artificial Intelligence and Digital Economy (SZ) · Sun Yat-sen University · Tencent

---

## 🌟 Introduction

**WEVSR** is a new Real-World Video Super-Resolution (RealVSR) framework built upon WAN-2.1 to provide high-fidelity, temporally stable video restoration.  
It introduces two key innovations:

1. **Multi-Level Wavelet-Enhanced VAE Encoder**  
   Injects explicit high-frequency priors into the latent space using multi-level DWT, improving texture reconstruction while keeping the pretrained decoder unchanged.

2. **Fidelity-Aware Condition Controller**  
   A task-oriented adaptation strategy exploiting flow-based noise augmentation and timestep sampling to stabilize restoration and enhance detail recovery.

---

## 📦 Code Release

The official implementation of **WEVSR** is currently being prepared.

> **🔧 Code will be released soon.**  
> Please ⭐ star this repository to receive updates.

Planned release will include:

- Training & inference scripts
- Pretrained models
- Evaluation pipeline & benchmark configs

---

## 📚 Citation

```bibtex
@inproceedings{chen2026wevsr,
  title={WEVSR: Video Diffusion Generators for Real-World Video Super-Resolution with Wavelet-Enhanced VAE Encoder},
  author={Chen, Yuying and Liu, Zhirui and Jiang, Linyan and Gao, Qifan and Zhang, Xianguo and Gan, Jianhou and Ren, Wenqi},
  booktitle={International Conference on Machine Learning},
  year={2026}
}
