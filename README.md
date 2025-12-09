# CS483: Explainable Social Recommender System (CIAO and Epinions)

This repository contains the implementation of an **Explainable Social Recommender System** developed for the CS483 course.  

The project combines:

- Graph Autoencoders for **social graph denoising**
- SocialGCN for **social recommendation over user graphs**
- GAT based attention for **explainable social influence**
- SHAP based analysis for **feature level explanations**
- Evaluation on both **CIAO** and **Epinions** datasets
- Baselines for comparison against **Matrix Factorization** and **SocialGCN without denoising**

The codebase is organized into two independent pipelines:

1. **CIAO pipeline**  
2. **Epinions pipeline**

Each pipeline runs end to end: data loading, cleaning, graph construction, embedding learning, explainability, and evaluation.

---

## Repository structure

```text
CS483-ExplainableSRS/
│
├── README.md
├── requirements.txt
│
├── ciao/
│   ├── CS483_ExplainableSRS_CIAO.ipynb
│   └── data/
│       ├── raw/        ← Original CIAO dataset files
│  
│
└── epinions/
    ├── Epinions_CS483_ExplainableSRS_updated.ipynb
    └── data/
        ├── raw/        ← Original Epinions MAT files
       
