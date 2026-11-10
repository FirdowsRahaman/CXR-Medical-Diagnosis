# 🩺 CXR Medical Diagnosis & Multi-Label Classification

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Domain: Radiology](https://img.shields.io/badge/Domain-Radiology%20AI-indigo.svg)](#)
[![ROC-AUC](https://img.shields.io/badge/Metrics-ROC--AUC-brightgreen.svg)](#)

Multi-label diagnostic classification of thoracic diseases from chest radiographs with ROC-AUC curve analysis.

## 📌 Overview
Computer-aided diagnosis (CAD) framework for detecting multiple co-occurring thoracic conditions (e.g., Cardiomegaly, Effusion, Infiltration, Mass, Nodule, Pneumothorax) from chest X-rays. Focuses on rigorous clinical evaluation using multi-label receiver operating characteristic (ROC) curves and Area Under Curve (AUC) statistics.

## 🛠️ Methodology & Features
- **Multi-Label Cross-Entropy:** Handling non-mutually exclusive radiological findings.
- **Threshold Calibration:** Optimizing decision thresholds per finding to balance true positive rate (TPR) and false positive rate (FPR).
- **ROC-AUC Visualizations:** Comprehensive multi-pathology performance curves.

## 📂 Repository Contents
- `Chest X-Ray Diagnosis ROC Curve.ipynb`: Complete evaluation pipeline generating ROC curves, optimal threshold sweeps, and macro/micro AUC scores.

## 🚀 Quickstart
```bash
git clone https://github.com/FirdowsRahaman/CXR-Medical-Diagnosis.git
cd CXR-Medical-Diagnosis
pip install torch torchvision numpy pandas matplotlib scikit-learn
jupyter notebook "Chest X-Ray Diagnosis ROC Curve.ipynb"
```

## 📄 License
This project is licensed under the MIT License.
