# Advanced Forecasting of Walmart Sales Using Deep Learning

This project extends a previous retail forecasting model by integrating macroeconomic indicators and advanced deep learning techniques. Built as a final project for DATA698 (Advanced Deep Learning) in the UMBC Data Science MPS program, this notebook explores whether external signals like GDP, inflation, and consumer sentiment can improve sales predictions.

---

## 🔍 Problem Statement

Retail sales forecasting often focuses solely on internal transaction data. This project aims to evaluate whether macroeconomic indicators (GDP, CPI, UMCSENT) enhance predictive accuracy when combined with Walmart's historical weekly sales data.

---

## 📈 Data Sources

* **Walmart Historical Sales** (Kaggle)
  [Walmart Store Sales Forecasting](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting)

* **Macroeconomic Indicators:**

  * **GDP** from FRED (Federal Reserve Economic Data)
  * **CPI (Consumer Price Index)** from FRED
  * **UMCSENT (Consumer Sentiment Index)** from University of Michigan / FRED

Datasets were merged and resampled to a daily time series aligned across all indicators.

---

## 📊 Methods & Model Architecture

* Data preprocessing with `pandas`, `numpy`, and `matplotlib`
* Custom dataset creation and batching using PyTorch `DataLoader`
* Deep learning architecture included:

  * Fully-connected layers with custom training loop
  * (Optional) Recurrent or attention-based layers
  * Dropout and batch normalization
* Evaluation via RMSE and visual inspection of training/test curves

---

## 🎓 Learning Outcomes

* Implemented advanced training pipelines and loss tracking from scratch in PyTorch
* Learned to incorporate real-world economic data into time series forecasting models
* Explored trade-offs in model complexity, overfitting, and data alignment

---

## 📁 Repo Structure

```
advanced-forecasting-walmart/
├── notebooks/
│   └── Final_Project_v5.ipynb      # Deep learning forecast notebook
├── data/                              # (Optional)
├── thumbnail.png                      # GitHub/LinkedIn preview image
└── README.md
```

---

## 📇 Credits

Final project for DATA698: Advanced Deep Learning
University of Maryland, Baltimore County (UMBC) – MPS in Data Science
Author: Craig Drohan
