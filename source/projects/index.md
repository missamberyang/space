---
title: Projects
date: 2025-04-06 17:18:14
---
## ⚗️ AI for Chemistry: Predicting Photovoltaic Efficiency Using Explainable ML

**Goal**: Predict the Power Conversion Efficiency (PCE) of organic photovoltaic (OPV) materials using ML to accelerate high-efficiency solar material discovery.

**Dataset**: Harvard Organic Photovoltaic Dataset (HOPV15)

**Approach**:
- Built a pipeline using **XGBoost** and **Random Forest** for feature selection and regression.
- Prioritized chemical descriptors: **LUMO**, **HOMO**, **Morgan fingerprints**, and **PubChem fingerprints**.
- Applied **SHAP** to interpret feature contribution and interactions.

**Key Insights**:
- **LUMO** was the strongest predictor of PCE, followed by **HOMO**.
- SHAP interaction analysis identified specific fingerprint bits as strong indicators of high efficiency.
- **PubChem bit** correlated with low PCE due to disrupted charge transport.

**Results**:
- 📊 **R² = 0.918**, **RMSE = 0.302**, **MAE = 0.148** on the test set
- Achieved **state-of-the-art performance** on HOPV15 with interpretable outcomes.

**Impact**:
- Provided a framework for **high-throughput OPV material screening**.
- Facilitated the **design of next-gen solar materials** by linking structure to performance.

**Skills demonstrated**:
- Supervised learning with **XGBoost**, **Random Forest**
- Feature engineering and domain-specific descriptor selection
- Model interpretability using **SHAP & SHAP interaction**
- Scientific communication and metric-driven model evaluation

### 💼 Want to know more?
This project is part of my published research. I'm happy to discuss the pipeline or results during interviews!

[📄 Read the paper](#tbd)

---
