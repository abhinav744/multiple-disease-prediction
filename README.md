# 🩺 Multiple Disease Prediction

A comprehensive machine learning project that predicts the likelihood of multiple diseases from user input—integrating models for diseases like diabetes, heart disease, Parkinson's disease within a Streamlit-powered web interface.

[Multiple Disease Prediction App](https://multiple-disease-prediction-fyim3hmmooqlgxb6yrb5tw.streamlit.app/)

## 🚀 Project Overview

Goal: Enable users to check the probability of multiple diseases through a single, intuitive platform.

Diseases Covered:

Diabetes

Heart Disease

Parkinson’s Disease

Tech Stack:

Python

ML libraries: scikit-learn (SVM, Logistic Regression, Random Forest)

Streamlit for the frontend web app

## 📂 Repository Structure

/multiple-disease-prediction

├── app.py                  # Streamlit interface

├── model_scripts/          # Scripts or notebooks for training each disease model

├── models/                 # Saved models (e.g. .pkl or .sav files)

├── requirements.txt        # Project dependencies

└── README.md               # This documentation

## ⚡ Getting Started

### 1. Clone the repository

git clone https://github.com/abhinav744/multiple-disease-prediction.git

cd multiple-disease-prediction

### 2. (Optional) Create a virtual environment

python -m venv venv

source venv/bin/activate    # On Windows: venv\Scripts\activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Run the Streamlit App

streamlit run app.py

## 📊 Insights & Benchmarks

Models typically perform with accuracy above 85–90% depending on dataset and preprocessing.

Real-time probability scores for each disease enhance usability.

Designed for easy expansion—add more diseases or upgrade underlying algorithms as needed.

## 🔮 Future Enhancements

Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)

Add visual diagnostics (ROC curves, confusion matrices, SHAP values)

Support for more diseases (e.g., liver disease, lung disease, breast cancer)
