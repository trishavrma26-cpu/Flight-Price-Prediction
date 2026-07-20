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
Flight-Price-Prediction/
│
├── Clean_Dataset.csv
├── Flight_Price_Prediction.ipynb
├── flight_price_model.pkl
├── model_columns.pkl
├── README.md
└── requirements.txt

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies
3. Open the notebook
4. Run all cells.

---
## 📷 Screenshots
<img width="897" height="586" alt="image" src="https://github.com/user-attachments/assets/94ad79c2-2d42-4d9c-aff5-cf19ef80756e" />

****<img width="1272" height="471" alt="image" src="https://github.com/user-attachments/assets/3ae66f8a-0782-4af9-8979-3fa7ae559d00" />

<img width="923" height="678" alt="image" src="https://github.com/user-attachments/assets/ddb68f9e-2f83-49da-a71a-4fe7950622d5" />

## 📷 Results
Example outputs include:

- Distribution plots
- Correlation heatmap
- Feature importance
- Actual vs Predicted graph

(Add screenshots below)

---

## 🔮 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- LightGBM implementation
- Flask/Streamlit Web Application
- Flight Price Prediction API
- Real-time flight data integration

---

## 👩‍💻 Author

**Trisha Verma**

