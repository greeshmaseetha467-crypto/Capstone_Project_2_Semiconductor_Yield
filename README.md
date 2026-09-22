# Capstone Project 2 – Semiconductor Yield Prediction

## 📌 Project Overview

This project focuses on predicting **Pass/Fail yield in a semiconductor manufacturing process** using sensor and process measurement data.

The project was completed as **Capstone Project 2** as part of the Corizo internship program.

The dataset contains a large number of sensor measurements. The objective is to build a reliable classification system and analyse whether all measured signals are required for predicting semiconductor yield.

---

## 🎯 Project Objective

The main objectives of this project are:

- Explore and understand semiconductor sensor data.
- Clean and preprocess the dataset.
- Identify missing, constant and redundant features.
- Perform univariate, bivariate and multivariate analysis.
- Identify and handle class imbalance.
- Apply feature preprocessing and dimensionality reduction.
- Train and compare multiple supervised machine learning models.
- Perform cross-validation and hyperparameter tuning using GridSearchCV.
- Evaluate models using appropriate classification metrics.
- Select a final model based on cross-validation performance.
- Save the trained model for future use.

---

## 📊 Dataset

The dataset contains:

| Property | Description |
|---|---|
| Domain | Semiconductor Manufacturing |
| Observations | 1,567 |
| Original Features | 591 |
| Target | Pass / Fail Yield |
| Pass Label | `-1` |
| Fail Label | `1` |

The dataset contains sensor and process measurement variables collected from semiconductor production entities.

The target variable represents the yield result of each production entity.

### Class Distribution

The dataset is highly imbalanced, with Pass observations substantially outnumbering Fail observations.

Therefore, model evaluation does not rely only on overall accuracy. Particular attention is given to the **Fail-class Precision, Recall and F1-score**.

---

## 🔬 Project Workflow

The project follows an end-to-end machine learning workflow:

```text
Data Import
     ↓
Data Exploration
     ↓
Data Cleansing
     ↓
Exploratory Data Analysis
     ↓
Train-Test Split
     ↓
Feature Preprocessing
     ↓
Standardisation
     ↓
SMOTE Class Balancing
     ↓
Model Training
     ↓
5-Fold Stratified Cross-Validation
     ↓
GridSearchCV Hyperparameter Tuning
     ↓
Model Evaluation
     ↓
Model Comparison
     ↓
Final Model Selection
     ↓
Model Saving
