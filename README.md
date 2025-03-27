# 📊 Dimensionality Reduction & Stock Price Prediction

## 📌 Project Overview
This project focuses on two key data science techniques:

1. **Dimensionality Reduction** using Principal Component Analysis (**PCA**) for visualization.
2. **Stock Price Prediction** using **Time Series Forecasting with ARIMA**.

---

## 🛠 Technologies Used
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🎨
- Scikit-Learn 🤖
- Statsmodels 📉

---

## 📂 Project Structure
```
📁 Dimensionality-Reduction-Stock-Prediction/
│── 📄 README.md
│── 📄 stock_prices.csv
│── 📜 pca_analysis.py
│── 📜 arima_forecasting.py
│── 📜 requirements.txt
```

---

## 🏆 Part 1: Dimensionality Reduction using PCA
### 🔹 Objective
Reduce high-dimensional data to **2D** for visualization.

### 🔹 Steps
1. Load a high-dimensional dataset (**Iris dataset** used in this project).
2. Apply **PCA** to reduce dimensions to **2 principal components**.
3. Visualize the reduced data using a **scatter plot**.

### 📊 Output
✅ **Reduced dataset (2D representation)**  
✅ **Scatter plot of PCA results**


---

## 🏆 Part 2: Stock Price Prediction using ARIMA
### 🔹 Objective
Forecast future stock prices based on historical data.

### 🔹 Dataset
- **File:** `stock_prices.csv`
- **Columns:**
  - Date (Timestamp)
  - Open (Opening price)
  - Close (Closing price)
  - Volume (Trade volume)

### 🔹 Steps
1. **Load & Preprocess Data**: Convert `Date` to `datetime`, handle missing values, set `Date` as the index.
2. **Exploratory Data Analysis (EDA)**: Analyze trends, seasonality, and noise.
3. **Feature Engineering**: Create lag features, moving averages, and other time-series transformations.
4. **Model Training**: Train an **ARIMA (p, d, q)** model for forecasting.
5. **Model Evaluation**: Compare actual vs. predicted stock prices using **MAE, RMSE, MAPE**.

### 📊 Output
✅ **Trained ARIMA model**  
✅ **Time-series plots comparing actual vs. predicted prices**  
✅ **Forecasting errors (MAE, RMSE, MAPE)**  



---


#DataScience #MachineLearning #PCA #ARIMA #StockPrediction #Python
