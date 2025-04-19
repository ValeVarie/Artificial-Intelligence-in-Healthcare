# AI-Driven Drug Sensitivity Prediction in Cancer Cell Lines for Precision Medicine

This repository contains the complete coursework project for **SAT 5114 – Artificial Intelligence in Healthcare**, conducted at Michigan Technological University. The project utilizes machine learning techniques to predict drug sensitivity in cancer cell lines using genomic and pharmacological data from the Genomics of Drug Sensitivity in Cancer (GDSC) dataset.

## 👥 Authors

- **Valeria V. Mudzindiko**
- **Miltone Awiti**

> Instructor: Dr. Guy Hembroff  
> Course: SAT 5114 – AI in Healthcare  
> Group: 29

---

## 📌 Project Objectives

- Develop machine learning models to predict cancer cell line responses to various drug compounds.
- Identify genomic and molecular biomarkers influencing drug sensitivity.
- Evaluate and compare performance across different AI models.
- Apply SHAP values to enhance model transparency and clinical trust.

---

## 🧬 Dataset Description

- **Source**: [GDSC on Kaggle](https://www.kaggle.com/code/samiraalipour/genomics-of-drug-sensitivity-in-cancer)
- **Size**: 484,071 samples from GDSC1 & GDSC2
- **Contents**:
  - 1,002 cancer cell lines
  - 621 drugs
  - Features: IC50, gene expression, mutation status, and tissue type

---

## 🤖 Machine Learning Models

| Model                  | Description |
|------------------------|-------------|
| Logistic Regression    | Baseline binary classification model |
| Random Forest          | Ensemble model with high accuracy and interpretability |
| XGBoost                | Boosted trees optimized for structured data |
| Support Vector Machine (SVM) | Effective in high-dimensional feature spaces |
| K-Nearest Neighbors (KNN) | Distance-based model for classification benchmarking |

---

## 📊 Performance Evaluation

Models were assessed using:

- Accuracy
- Precision
- Recall
- F1 Score
- R² Score
- Confusion Matrix
- SHAP Value Analysis (for feature importance)

**Top Performer**: Random Forest  
**Notable Mention**: XGBoost performed closely behind with excellent generalization and model robustness.

---

## 📈 Results Summary

- Random Forest achieved the highest prediction accuracy.
- SHAP analysis identified key genetic markers affecting drug sensitivity.
- Tissue-specific accuracy revealed variable performance across cancer types.
- Models were trained, tuned, and interpreted to ensure clinical relevance.

---

## 🛠️ Methodology

1. **Data Cleaning**: Removed irrelevant columns, handled missing values
2. **Feature Engineering**: Selected key features for modeling
3. **Model Training & Tuning**: Trained and tuned 5 different AI models
4. **Interpretability**: Applied SHAP to explain predictions
5. **Validation**: Compared results to existing research benchmarks

---

## 🚀 Future Work

- Integrate **deep learning** models (CNNs, Autoencoders)
- Address **class imbalance** via SMOTE or weighted losses
- Include **multi-omics data** for broader insights
- Build an **AI-powered Clinical Decision Support System (CDSS)**

---
## Presentation video can be found here
https://youtu.be/LQhw5dnDi2s


