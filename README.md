# ✈️ Flight Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)
![License](https://img.shields.io/badge/License-MIT-green)


A Machine Learning project that predicts flight ticket prices based on airline, source, destination, travel class, duration, number of stops, departure/arrival time, and days left before departure.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction using a Random Forest Regressor.

---

## 📌 Project Overview

The objective of this project is to build an accurate machine learning model capable of predicting flight prices using historical flight data.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Encoding
- Model Training
- Model Evaluation
- Model Saving using Pickle

---
## 🎯 Objectives

- Analyze flight pricing patterns.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Build a Machine Learning model for price prediction.
- Compare model performance using evaluation metrics.
- Save the trained model for future deployment.


## 📊 Dataset Information

Dataset: **Clean_Dataset.csv**

Features used:

- Airline
- Source City
- Destination City
- Departure Time
- Arrival Time
- Number of Stops
- Travel Class
- Duration
- Days Left
- Price (Target Variable)

Dataset Size:

- **300,153 rows**
- **11 input features**
- **1 target column (Price)**

---

## 🔍 Exploratory Data Analysis (EDA)

Performed various EDA techniques including:

- Distribution of Flight Prices
- Airline-wise Price Analysis
- Travel Class Comparison
- Source & Destination Analysis
- Stops vs Price
- Duration vs Price
- Correlation Heatmap
- Outlier Detection using Boxplots

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Handled categorical variables
- Ordinal Encoding for:
  - Stops
  - Class
- One-Hot Encoding for:
  - Airline
  - Source City
  - Destination City
  - Departure Time
  - Arrival Time
- Train-Test Split (80-20)

---

## 🤖 Machine Learning Model

Model Used:

- Random Forest Regressor
Why Random Forest?

- High Prediction Accuracy
- Handles Non-linear Relationships
- Robust to Outliers
- Reduces Overfitting using Ensemble Learning

  
Libraries:
- Scikit-Learn
- Pandas
- NumPy

---

## 📈 Model Performance

| Metric | Value |
|---------|--------|
| R² Score | **0.98+** |
| MAE | **~1100** |
| RMSE | **~2800** |

The Random Forest model achieved excellent prediction accuracy with a high R² score and low prediction error.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Pickle
- Git
- GitHub

---

## 📂 Project Structure

Flight-Price-Prediction/
│
├── Clean_Dataset.csv
├── Flight_Price_Prediction.ipynb
├── flight_price_model.pkl
├── model_columns.pkl
├── requirements.txt
├── README.md
└── images/
---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies
3. Open the notebook
4. Run all cells.

---

## 📷 Results
Example outputs include:

- Distribution plots
- Correlation heatmap
- Feature importance
- Actual vs Predicted graph

---

## 📷 Plots
<img width="897" height="586" alt="image" src="https://github.com/user-attachments/assets/94ad79c2-2d42-4d9c-aff5-cf19ef80756e" />

****<img width="1272" height="471" alt="image" src="https://github.com/user-attachments/assets/3ae66f8a-0782-4af9-8979-3fa7ae559d00" />

<img width="923" height="678" alt="image" src="https://github.com/user-attachments/assets/ddb68f9e-2f83-49da-a71a-4fe7950622d5" />

---
## 📚 Key Learning Outcomes

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Machine Learning Pipeline
- Model Evaluation
- Git & GitHub
- Model Serialization using Pickle


