# CS483 — Explainable Social Recommender System (CIAO + Epinions)

This repository contains the full implementation of an **Explainable Social Recommender System** developed for **CS483**.  
The project integrates:

- Graph Autoencoders for **denoising social graphs**
- SocialGCN for **recommendation with social propagation**
- GAT-based explainability for **interpretable social attention**
- SHAP explanations for **feature-level contribution analysis**
- Evaluation across **CIAO** and **Epinions** datasets
- Baselines (Matrix Factorization + SocialGCN Raw)

The project is organized into two independent pipelines:

1. **CIAO Recommender System**
2. **Epinions Recommender System**

Both pipelines follow the same full workflow:
data cleaning, graph construction, embedding learning, explainability, and evaluation.

---

## 📁 Repository Structure
