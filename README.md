# fraud-detection-ml

A machine learning project for detecting fraudulent credit card transactions using Python.
This repository contains scripts and a Jupyter notebook for building and evaluating fraud detection models.

---

## Repository Contents

- `fraud-detection-ml.py` — Main Python script with the full ML workflow
- `fraud-detection-ml.ipynb` — Jupyter notebook version for interactive exploration
- `README.md` — Project documentation

---

## Project Overview

This project demonstrates how to detect fraudulent credit card transactions using supervised machine learning. The workflow includes:

- Data loading and inspection
- Exploratory data analysis and class balancing
- Data preprocessing
- Training multiple models: Logistic Regression, Random Forest, and XGBoost
- Model evaluation and selection
- Hyperparameter tuning with GridSearchCV
- Making predictions on new transactions

---

## Download the Dataset

To run this project, you need the `creditcard.csv` dataset. Follow these steps:

1. **Download the dataset from Kaggle:**
   
   - Visit [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
   - Click on the **Download** button.
2. **Place the CSV file:**
   
   - After downloading, locate the `creditcard.csv` file on your computer.
   - Move or copy `creditcard.csv` into the root directory of this repository (the same folder as your `.py` and `.ipynb` files).

---

## 📝 How to Use

1. **Clone the repository:**
   
   ```
   git clone https://github.com/your-username/fraud-detection-ml.git
   cd fraud-detection-ml
   ```
2. **Install dependencies:**
   
   ```
   pip install pandas scikit-learn matplotlib seaborn xgboost
   ```
3. **Download the dataset as described above and place it in the project folder.**
4. **Run the Python script:**
   
   ```
   python fraud-detection-ml.py
   ```
   
   *or open the notebook:*
   
   ```
   jupyter notebook fraud-detection-ml.ipynb
   ```




