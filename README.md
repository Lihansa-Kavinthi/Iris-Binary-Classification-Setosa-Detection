# Iris Binary Classification: Setosa Detection 🌸

This repository contains a machine learning workflow focused on binary classification using the famous Iris dataset. The project demonstrates the implementation of Logistic Regression and Random Forest models to identify the **Setosa** species.

## 🚀 Project Overview

The objective of this notebook is to build and evaluate predictive models that can distinguish between the 'Setosa' species and other iris species. It covers the end-to-end ML pipeline:
- Data Loading and Transformation
- Feature Scaling
- Model Training (Logistic Regression & Random Forest)
- Performance Evaluation (ROC Curves & Classification Reports)

## ✨ Key Features

- **Binary Target Engineering**: Converts the multi-class Iris dataset into a binary classification problem (Setosa vs. Non-Setosa).
- **Standardization**: Implements `StandardScaler` to normalize feature ranges for optimal model convergence.
- **Model Comparison**: Benchmarks a baseline **Logistic Regression** model against an ensemble **Random Forest Classifier**.
- **Visualization**: Generates a **Receiver Operating Characteristic (ROC)** curve to visualize the True Positive Rate vs. False Positive Rate and calculates the **AUC (Area Under Curve)**.

## 📊 Performance Summary

The models achieved high performance metrics on the test set:
- **Logistic Regression Accuracy**: 1.00 (100%)
- **Random Forest Accuracy**: 1.00 (100%)
- **AUC Score**: 1.00

### Classification Report (Sample Output)
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Non-Setosa (0) | 1.00 | 1.00 | 1.00 |
| Setosa (1) | 1.00 | 1.00 | 1.00 |

## 🛠️ Technical Stack

- **Python**: Core programming language.
- **Scikit-Learn**: For dataset loading, splitting, scaling, and modeling.
- **Matplotlib & Seaborn**: For creating performance visualizations.
- **Pandas & NumPy**: For efficient data handling.

## 📂 How to Run

1. Clone this repository.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
