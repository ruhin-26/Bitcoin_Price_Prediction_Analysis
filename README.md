<div align="center">

# ₿ Bitcoin Price Prediction — Time Series Analysis with Machine Learning

### Predicting the direction of Bitcoin's next-day price movement using EDA, feature engineering & classification models

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Models-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-EB0028?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

---

## 📌 Overview

This project analyzes historical **Bitcoin price data** as a time series and builds a **machine learning classification model** to predict whether the next day's closing price will go **up or down**. It combines classic exploratory data analysis, date-based feature engineering, and comparison of multiple ML models to find the best predictor of short-term price direction.

---

## ✨ Key Features

| Category | What's Inside |
|---|---|
| 📉 **Time Series EDA** | Visualizing Bitcoin's closing price trend over time |
| 🧹 **Data Cleaning** | Dropping redundant columns, checking for null values |
| 📊 **Distribution Analysis** | Distplots & boxplots for Open, High, Low, Close prices |
| 🛠️ **Feature Engineering** | Extracting year/month/day, quarter-end flags, open-close & low-high spreads |
| 🎯 **Target Creation** | Binary target — will tomorrow's close be higher than today's? |
| 🔗 **Correlation Analysis** | Heatmap to detect highly correlated features |
| 🤖 **Model Building** | Logistic Regression, SVM (poly kernel), XGBoost Classifier |
| 📈 **Model Evaluation** | ROC-AUC score, Confusion Matrix, Classification Report |

---

## 🗂️ Dataset

| File | Description |
|---|---|
| `bitcoin.csv` | Historical daily OHLC (Open, High, Low, Close) & Adjusted Close prices for Bitcoin |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas / NumPy** — data manipulation
- **Matplotlib / Seaborn** — exploratory visualization
- **Scikit-learn** — preprocessing, train/test split, Logistic Regression, SVM, evaluation metrics
- **XGBoost** — gradient boosting classifier
- **Jupyter / Colab Notebook**

---

## 🚀 Project Workflow

```
1. Import Libraries          →  numpy, pandas, matplotlib, seaborn, sklearn, xgboost
2. Load Dataset               →  bitcoin.csv
3. Exploratory Data Analysis  →  plot closing price trend, check shape & info
4. Data Cleaning              →  drop 'Adj Close', check nulls
5. Distribution Analysis      →  distplots & boxplots for OHLC features
6. Feature Engineering        →  extract year/month/day, quarter-end flag,
                                  open-close spread, low-high spread
7. Target Variable            →  binary label — next day price up (1) or down (0)
8. Correlation Heatmap        →  detect redundant/highly-correlated features
9. Train-Test Split & Scale   →  StandardScaler on selected features
10. Model Training             →  Logistic Regression, SVM, XGBoost
11. Model Evaluation           →  ROC-AUC score, confusion matrix, classification report
```

---

## 📁 Repository Structure

```
Bitcoin-Price-Prediction-Time-Series-Analysis/
│
├── Bitcoin_Price_Prediction_Analysis.ipynb   # Main notebook
├── bitcoin.csv                                # Historical price dataset
└── README.md                                  # You are here
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/Bitcoin-Price-Prediction-Time-Series-Analysis.git
cd Bitcoin-Price-Prediction-Time-Series-Analysis

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter

# 3. Launch the notebook
jupyter notebook Bitcoin_Price_Prediction_Analysis.ipynb
```

---

## 📷 Sample Visuals

> Add screenshots of the closing price trend, correlation heatmap, and confusion matrix here — visuals massively boost engagement on GitHub & LinkedIn.

```
docs/
├── closing-price-trend.png
├── correlation-heatmap.png
└── confusion-matrix.png
```

---

## 🎯 What This Project Demonstrates

- Treating financial data as a proper time series (date parsing, trend visualization)
- Engineering meaningful features from raw date & price columns
- Framing a prediction problem as binary classification (direction, not exact price)
- Comparing multiple ML models fairly using ROC-AUC and classification metrics
- Understanding the limits of predicting noisy financial markets

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

---

<div align="center">

**⭐ If you found this project useful, consider giving it a star!**

</div>
