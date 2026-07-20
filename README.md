# ✈️ Flight Price Prediction using Machine Learning

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
