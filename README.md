# Meta Stock Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on historical stock data of **Meta Platforms Inc. (META)** using Python. The objective is to analyze long-term stock behavior, identify major trends, study price movements, and determine important features that can be useful for future stock price prediction models.

---

## 🎯 Objectives

* Analyze the historical performance of Meta stock.
* Study trends in opening, closing, high, and low prices.
* Examine daily returns and cumulative returns.
* Analyze market volatility and price spreads.
* Identify important parameters that may influence future stock movements.
* Generate visual insights through statistical analysis and graphical representations.

---

## 📂 Dataset

* **Company:** Meta Platforms Inc. (META)
* **Data Type:** Historical stock market data
* **Features Used:**

  * Date
  * Open Price
  * High Price
  * Low Price
  * Close Price
  * Volume

Additional features created during analysis:

* Daily Return
* Cumulative Return
* High-Low Spread
* Open-Close Spread
* Year
* Month
* Quarter
* Day of Week

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Jupyter Notebook

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* SciPy

---

## 📊 Analysis Performed

### Basic Data Exploration

* Dataset overview
* Missing value analysis
* Data type inspection
* Descriptive statistics

### Price Trend Analysis

* Closing price trends over time
* Open vs Close price comparison
* High-Low spread analysis

### Return Analysis

* Daily returns
* Cumulative returns

### Volatility Analysis

* Intraday volatility using High-Low spread
* Bullish and bearish movement using Open-Close spread

### Visualization

* Line plots
* Area plots
* Candlestick charts
* Statistical graphs

---

## 📈 Key Insights

* Meta stock exhibits significant growth over the long term despite periods of volatility.
* Major market events such as the COVID-19 crash and the 2022 decline impacted stock prices considerably.
* Daily returns and volatility measures provide valuable information regarding market behavior.
* Derived features such as returns and spreads can serve as useful inputs for future machine learning-based stock prediction models.

---

## 🚀 Future Scope

* Build stock price forecasting models using Machine Learning.
* Apply LSTM and other deep learning techniques for time-series prediction.
* Perform technical indicator analysis.
* Compare Meta stock with other major technology companies.
* Develop interactive dashboards for real-time analysis.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/meta-stock-eda.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly scipy
```

3. Open the notebook:

```bash
Meta_Stock_EDA.ipynb
```

4. Run all cells to reproduce the analysis.

---

## 📷 Sample Visualizations

* Closing Price Trend
* Open vs Close Price Analysis
* Intraday Volatility
* Candlestick Chart
* Return Analysis

---

## 📜 Conclusion

This project provides a comprehensive exploratory analysis of Meta stock data and highlights important market patterns and features. The insights obtained from this analysis can serve as a strong foundation for future stock prediction and time-series forecasting models.
