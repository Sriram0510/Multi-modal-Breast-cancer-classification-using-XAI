# Explainable AI for Multi-Omics Breast Cancer Classification

## 🚀 Project Overview
This project focuses on the classification of early-stage (I/II) vs. late-stage (III/IV) breast cancer using a multi-omics approach. By integrating **Gene Expression, Proteomics, and Mutation data**, I developed a high-performance framework achieving near-perfect metrics.

* **Primary Metric:** 0.99 ROC-AUC / 0.98 F1-Score
* **Methodology:** Dimensionality reduction via **Deep Autoencoders** + **XGBoost Classifier**.
* **Explainability:** Integrated **SHAP and LIME** to identify key biomarkers (TP53, BRCA1).

## 📊 Technical Workflow
1. **Data Ingestion:** Processed TCGA-BRCA multi-omics data.
2. **Feature Engineering:** Statistical filtering (ANOVA) followed by 64-D Latent Space embedding.
3. **Model:** Optimized XGBoost pipeline with Hyperparameter tuning.
4. **XAI:** Global and Local interpretability to ensure clinical trust.

## 📁 Repository Structure
*  Contains the full training and evaluation pipeline.
*  Includes the full MSc Thesis and project presentation.
*  Small metadata files (Large datasets linked in 'Data' section).

## 🛠️ Installation
```bash
pip install -r requirements.txt
