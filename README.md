# 📊 Walmart Sales Analysis & Forecasting

## 📌 Overview

This project analyzes Walmart’s historical sales data to uncover trends, perform statistical analysis, and build predictive models. It combines **Exploratory Data Analysis (EDA)**, **hypothesis testing**, and **time series + machine learning models** to forecast sales.

---

## 🎯 Objectives

* Clean and preprocess real-world sales data
* Analyze sales trends across time and stores
* Perform statistical testing (Holiday vs Non-Holiday sales)
* Build forecasting models using:

  * Time Series (SARIMAX)
  * Machine Learning (Linear Regression)

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualization
* **SciPy** – Statistical testing (T-test)
* **Statsmodels** – SARIMA model
* **Scikit-learn** – Linear Regression

---

## 📂 Dataset

* Walmart weekly sales dataset
* Features include:

  * Store
  * Date
  * Weekly Sales
  * Holiday Flag
  * Other economic indicators

---

## 🔧 Data Preprocessing

* Converted `Date` column to datetime format
* Removed duplicate records
* Handled missing values
* Detected and removed outliers using **IQR method**

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analysis:

* 📈 Sales trend over time
* 🏪 Sales comparison across stores
* 📉 Distribution and summary statistics

---

## 📐 Statistical Analysis

### Hypothesis Testing:

* Performed **T-test** to compare:

  * Holiday sales vs Non-holiday sales

**Insight:**

* Checked whether holidays significantly impact sales using p-value

---

## 🤖 Modeling

### 1. Time Series Forecasting (SARIMAX)

* Applied on individual store data (Store 1)
* Used seasonal component (52 weeks)
* Captures:

  * Trend
  * Seasonality

---

### 2. Machine Learning Model (Linear Regression)

* Features used: economic and store-related variables
* Train-test split: 80/20
* Evaluated using:

➡️ **R² Score** (~0.02)

---

## 📈 Results

* Identified strong sales patterns over time
* Observed variation in sales across stores
* Statistical test revealed impact of holidays on sales
* Built:

  * Time series model for forecasting
  * Regression model for prediction

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/walmart-sales-forecasting.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn
```

3. Run the notebook

```bash
jupyter notebook
```

---

## 🙌 Conclusion

This project demonstrates how combining **data analysis, statistical methods, and predictive modeling** can generate valuable business insights and improve sales forecasting.

---
