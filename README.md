# 🍷 Wine Quality Analysis

This repository contains an analysis of wine quality data using various data balancing techniques such as Random Undersampling, Random Oversampling, SMOTE, and Tomek Links.

## 📁 Files

- `Untitled2 (3).ipynb` - Jupyter Notebook containing EDA, preprocessing, modeling, and evaluation.
- `untitled2 (2).py` - Python script version of key parts of the notebook.
- `archive.zip` - Contains the `wineqt.csv` dataset used for training and testing.

## 📊 Project Overview

The objective of this project is to:
- Analyze the wine quality dataset.
- Handle class imbalance in the quality labels.
- Train and evaluate classification models.
- Compare the effect of different balancing methods on model performance.

## ⚙️ Techniques Used

- **Data Preprocessing** (null handling, label distribution)
- **Train-Test Split**
- **Balancing Methods**:
  - Random Undersampling
  - Random Oversampling
  - SMOTE
  - Tomek Links
- **Model Evaluation**:
  - Precision, Recall, F1-score
  - AUC Score

## 🧪 Evaluation Metrics

Each method is evaluated based on classification metrics such as accuracy, macro and weighted averages, and AUC score.

## 📦 Requirements

- Python
- scikit-learn
- imbalanced-learn
- pandas
- matplotlib / seaborn
- Jupyter Notebook

Install using:

```bash
pip install -r requirements.txt
