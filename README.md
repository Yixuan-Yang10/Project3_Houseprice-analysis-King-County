# Project3_Houseprice-analysis-King-County
# 🏠 King County Housing Price Analysis (2014–2015)

## 📋 Project Overview

This project explores housing price data from **King County, Washington** (2014–2015) using **R**. The main goals were to:

- Understand which factors most influence housing prices
- Build predictive models for estimating future prices
- Provide actionable business insights for home buyers and sellers

---

## 🧹 Data Cleaning & Preparation

Before modeling, we cleaned and prepared the dataset by:

- **Removing outliers** and erroneous entries
- **Converting data types** (e.g., date fields, numerical conversions)
- **Splitting the dataset** into training and test sets

---

## 📊 Exploratory Data Analysis (EDA)

We explored the relationships in the data using:

- **Summary statistics** (mean, median, etc.)
- **Correlation matrix** to identify linear relationships
- **Histograms** to understand distribution of key variables
- **Scatterplots** to explore pairwise trends (e.g., price vs. living space)

---

## 🔍 Modeling Techniques

To analyze price drivers and make predictions, we applied both **regression** and **classification** methods:

### 📈 Regression Models:
- **Multiple Linear Regression**
- **Ridge Regression**
- **Random Forest Regression**

These models helped assess which features (e.g., living space, condition, quality) have the strongest impact on price and which model performs best for prediction.

### 🧠 Classification Analysis:
We used classification techniques to categorize housing prices and uncover the most influential features behind pricing tiers.

---

## 💡 Key Findings

- **Living space size** and **Location** are the most influential features affecting home prices.
- Clear business insights emerged for:
  - 🏘️ **Buyers**: Focus on homes with good location and efficient square footage.
  - 💼 **Sellers**: Renovating to improve perceived quality can raise sale prices.

---

## 🛠️ Tools & Packages Used

- **Language:** R
- **Libraries:** `ggplot2`, `randomForest`, `glmnet`, `pls`, `tree`, etc

---
