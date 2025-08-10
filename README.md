# Bike-Rentals-Forecasting-with-Time-Series-Models-SARIMA-Prophet-
# 🚲 Bike Rentals Forecasting with Time-Series Models (SARIMA & Prophet)

This project predicts **daily bike rental counts** using historical data from the **UCI Bike Sharing Dataset (`day.csv`)**.  
It implements and compares **Seasonal ARIMA (SARIMA)** and **Facebook Prophet** models for time-series forecasting.

---

## 📊 Features
- **Data Preprocessing & Cleaning**
  - Convert `dteday` to datetime
  - Sort by date & remove duplicates
  - Select only `cnt` (total rentals) for modeling
- **Exploratory Data Analysis (EDA)**
  - Visualize trends, seasonality, and patterns
- **Forecasting Models**
  - Seasonal ARIMA (SARIMA) with `pmdarima`
  - Prophet with yearly seasonality
- **Evaluation**
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- **Visualization**
  - Forecast vs Actual plots for both models

---

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository – Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
- **File Used:** `day.csv`
- **Key Columns:**
  - `dteday` → Date of rentals
  - `cnt` → Total daily rentals

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `statsmodels`, `pmdarima`
  - `prophet`
  - `scikit-learn`

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YourUsername/bike-rentals-forecasting.git
cd bike-rentals-forecasting
🙌 Acknowledgements
Dataset: UCI Machine Learning Repository – Bike Sharing Dataset

SARIMA: pmdarima library

Prophet: Developed by Facebook (Meta)
