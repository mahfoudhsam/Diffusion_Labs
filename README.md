# Diffusion Labs

A hands-on learning and research repository on diffusion models, generative modeling, and the mathematics behind them.

The goal is to build a deep understanding of diffusion mechanisms through derivations, implementations, visualizations, and controlled experiments.

---

## Table of Contents

- [Learning Roadmap](#learning-roadmap)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Methodology](#methodology)
- [Lab 1 Notes](#lab-1-notes)
- [References and Acknowledgments](#references-and-acknowledgments)

---

## Learning Roadmap

| Lab | Topic | Status |
| --- | --- | --- |
| Lab 1 | Introduction to Diffusion Models | In progress |
| Lab 2 | Denoising Diffusion Probabilistic Models (DDPM) | Planned |
| Lab 3 | Denoising Diffusion Implicit Models (DDIM) | Planned |
| Lab 4 | Score-Based Generative Models | Planned |
| Lab 5 | Flow Matching | Planned |
| Lab 6 | Guidance and Conditioning | Planned |
| Lab 7 | Reinforcement Learning for Diffusion Models | Planned |

---

## Repository Structure

```
diffusion-labs/
├── README.md
└── labs/
    ├── lab_one_DDPM_Fundamentals.ipynb
    └── ...
```

---

## Getting Started

The notebooks run on Google Colab or locally.

**Requirements**

- Python 3.10+
- PyTorch
- NumPy
- Matplotlib
- tqdm
- Jupyter (for local use)

**Local setup**

```bash
git clone <https://github.com/mahfoudhsam/Diffusion_Labs>
cd diffusion-labs
pip install torch numpy matplotlib tqdm jupyter
jupyter notebook labs/lab_one.ipynb
```

---

## Methodology

Each lab combines:

1. **Theory**: mathematical foundations and derivations.
2. **Implementation**: code and code analysis.
3. **Visualization**: plots of model behavior.
4. **Experiments**: parameter sweeps and comparisons.
5. **Observations**: research notes and open questions.

---

## Lab 1 Notes

Topics covered so far:

- Simulating SDEs with the Euler-Maruyama method
- Brownian motion: the effect of `sigma` on the spread of trajectories (std = σ√t)
- Ornstein-Uhlenbeck process: the effect of `theta` (mean reversion) on trajectories

Open questions and findings are added to the notebook as they come up.

---

## References and Acknowledgments

Learning materials and original implementations are credited to their respective authors and research groups.

Original Lab 1 material: <https://github.com/eje24/iap-diffusion-labs/blob/2026/labs/lab_one.ipynb>

> This repository is an independent learning and experimentation project. It is not an official reproduction or endorsement by the original authors.
