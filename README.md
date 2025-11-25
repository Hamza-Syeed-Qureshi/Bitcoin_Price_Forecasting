# ₿ Bitcoin Price Forecasting using Machine Learning & Time Series Analysis

## 📌 Project Overview
This project focuses on forecasting the price of **Bitcoin (BTC-USD)** using machine learning and time series analysis techniques.  
The goal is to analyze historical BTC price trends, engineer meaningful features, and build predictive models to estimate future price movements.  
This project showcases skills in **data cleaning, visualization, feature engineering, model building, and evaluation**.

---

## 📂 Dataset Description
The dataset used in this project contains historical Bitcoin price data, including:

- **Date**
- **Open Price**
- **High Price**
- **Low Price**
- **Close Price**
- **Adjusted Close**
- **Volume**

This dataset provides a reliable foundation for understanding Bitcoin's volatility and price behavior over time.

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Loaded and cleaned BTC historical price data  
- Converted Date column to datetime format  
- Handled missing values  
- Sorted data chronologically  
- Created additional features such as:
  - Moving Averages (MA7, MA14, MA30)
  - Daily Returns
  - Price Volatility

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Line charts showing BTC price trends over time  
- Correlation heatmaps  
- Distribution plots of returns  
- Insights into volatility and long-term growth trends  

---

### 3️⃣ Model Development
Multiple models were tested for forecasting Bitcoin prices:

#### 📈 Traditional Machine Learning Models
- Linear Regression  
- Random Forest Regressor  
- Decision Tree Regressor  

#### 🕒 Time Series Models
- ARIMA / SARIMA  
- Moving Average Models  

#### 🤖 Deep Learning (optional if applied)
- LSTM Neural Network  
- RNN-based forecasting  

---

### 4️⃣ Model Evaluation
Models were evaluated using:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

Actual vs Predicted plots were used to visually assess model accuracy.

---

## 🧠 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Statsmodels  
- TensorFlow / Keras (for LSTM)  
- Jupyter Notebook  

---

