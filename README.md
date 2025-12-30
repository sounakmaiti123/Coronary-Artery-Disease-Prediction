# Early Prediction of Coronary Artery Disease using Ensemble Machine Learning

## 📖 Overview
Coronary Artery Disease (CAD) is one of the leading causes of mortality worldwide.
This project proposes an early risk prediction system using machine learning to
classify patient outcomes as **DISCHARGE**, **DAMA**, or **EXPIRY** based on clinical parameters.

An ensemble learning approach combining **XGBoost**, **Random Forest**, and
**Gradient Boosting** is used to improve predictive performance.

## 🚀 Features
- Data preprocessing with scaling and encoding
- Hyperparameter tuning using GridSearchCV
- Soft-voting ensemble classifier
- Performance evaluation using accuracy, confusion matrix, and ROC curves
- Patient-level risk prediction

## 🧠 Models Used
- Random Forest
- XGBoost
- Gradient Boosting
- Tuned Random Forest
- Ensemble (Soft Voting)

## 📊 Results
- Ensemble Model Accuracy: **~90.5%**
- Strong ROC-AUC across all classes
- Improved robustness over individual models

## 📁 Dataset
- Clinical dataset containing demographic, laboratory, and medical history features
- Target variable: `outcome` (DISCHARGE / DAMA / EXPIRY)

> Dataset used only for academic and research purposes.

## 🛠️ Installation
```bash
pip install -r requirements.txt

