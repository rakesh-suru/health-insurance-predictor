# 🏥 Health Insurance Cost Predictor

[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple Machine Learning project that predicts individual health insurance costs based on demographic and health-related attributes using **Linear Regression**.

---

## 🔍 Demo

<!-- Replace the link below with your image after uploading -->
![Actual vs Predicted Charges](screenshots/predicted_vs_actual.png)

---

## 📌 Project Overview

This project uses a dataset of patient information to estimate medical insurance charges. It applies **data preprocessing**, **EDA**, and **linear regression modeling** using `scikit-learn`.

---

## 📊 Dataset

- **File**: `insurance.csv`
- **Source**: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Features**:
  - `age`: Age of primary beneficiary
  - `sex`: Gender
  - `bmi`: Body mass index
  - `children`: Number of dependents
  - `smoker`: Smoking status
  - `region`: Residential area
  - `charges`: Medical insurance cost

---

## 📂 Project Structure

health-insurance-predictor/
├── data/
│ └── insurance.csv
├── notebooks/
│ └── health_insurance.ipynb
├── screenshots/
│ └── predicted_vs_actual.png
├── README.md
├── requirements.txt
└── LICENSE


---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rakesh-suru/health-insurance-predictor.git
cd health-insurance-predictor
