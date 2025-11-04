# Credit_Fraud_Analytics

This repository contains a **CatBoost-based fraud detection project** built on the NeurIPS 2022 BAF dataset (<1% fraud samples). The project benchmarks multiple classifiers, handles class imbalance, and implements a cost-sensitive decision framework.

---
## 🚀 Project Overview
- **Dataset:** NeurIPS 2022 BAF dataset (<1% fraud)
- **Task:** Binary fraud detection
- **Model:** CatBoost
- **Approach:**
  1. Benchmark 10 classifiers to find baseline performance.
  2. Handle class imbalance using **SMOTE + undersampling**.
  3. Design a **threshold-based two-layer decision framework**.
  4. Optimize thresholds with **Pyomo cost-sensitive modeling**.
- **Performance:**
  - ROC-AUC: **0.97**
  - Fraud recall: **0.96** on test set
---

## 📂 Repository Structure

### 1_Data
Contains dataset reference or link:
- `dataset_link.txt` → Contains the Kaggle dataset link. Users should download the dataset manually or via notebook.

### 2_Notebook
Contains the main code and documentation:
- `FraudDetection.ipynb` → Jupyter Notebook with full code, documentation, and explanations inline.
- `FraudDetection.pdf` → Exported PDF version of the notebook for easy sharing or submission.



