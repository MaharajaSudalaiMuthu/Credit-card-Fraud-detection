# 💳 Credit Card Fraud Detection

This project builds a machine learning model to detect fraudulent credit card transactions using a real-world dataset. The goal is to accurately identify fraudulent transactions while minimizing false positives.

---

## 📊 Dataset Information

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Total Transactions**: 284,807
- **Fraudulent Transactions**: 492 (~0.17%)
- **Features**:
  - `Time`, `Amount`, `V1` to `V28` (PCA-transformed)
  - `Class`: 0 (Normal), 1 (Fraud)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📌 Problem Statement

Due to the extremely imbalanced dataset, detecting fraud is challenging. The objective is to build a classification model that can:
- Accurately classify fraud cases
- Minimize false positives (legit transactions marked as fraud)
- Maximize recall (capture most frauds)

---

## 🧪 Project Workflow

1. **Load and explore the dataset**
2. **Preprocess data**
   - Normalize `Amount`
   - Drop `Time`
3. **Train/Test split**
4. **Train a Random Forest Classifier**
5. **Evaluate using confusion matrix and classification report**
6. **Visualize fraud distribution**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
