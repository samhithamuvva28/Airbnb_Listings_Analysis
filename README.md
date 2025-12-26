# Airbnb Pricing & Guest Satisfaction Analysis

This repository contains a final analysis notebook exploring **pricing dynamics, guest satisfaction, and demand patterns** in Airbnb listings across New York City.

The project applies **exploratory data analysis, feature engineering, and machine learning models** to understand key drivers of listing prices and to evaluate predictive approaches for optimal pricing strategies.

---

## 📊 Project Overview

- Dataset: NYC Airbnb listings (Kaggle)
- Rows: ~46,000 listings
- Target variable: `price`
- Key features: neighborhood, room type, availability, reviews, minimum nights

The analysis focuses on:
- Identifying factors that influence Airbnb pricing
- Comparing regression and classification models
- Interpreting results for real-world decision-making

---

## 🧠 Methods & Techniques

### Data Analysis
- Data cleaning and preprocessing
- Handling missing values and outliers
- Feature scaling and encoding
- Exploratory visualizations (price distributions, geographic trends, seasonality)

### Modeling
- **Logistic Regression**  
  - Classifies listings as above/below median price
- **Gradient Boosting Regressor (GBR)**  
  - Captures nonlinear pricing relationships
- **Random Forest Regressor (RFR)**  
  - Robust ensemble-based price prediction

### Evaluation
- RMSE for regression models
- Accuracy, precision, recall for classification
- Comparative performance analysis

---

## 📈 Key Insights

- Location and room type are the strongest price drivers
- Entire homes/apartments dominate both pricing and revenue
- Seasonal effects influence average prices across months
- Gradient Boosting achieved the best overall regression performance
- Model error (~$170 RMSE) is reasonable relative to market variability

---

## 📁 Repository Contents
analysis_code.ipynb 


- The notebook contains the **complete end-to-end analysis**, including data preprocessing, modeling, visualizations, and conclusions.

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🎯 Project Scope

This project emphasizes **analytical reasoning and applied machine learning** rather than production deployment or pipeline engineering.

It is intended to demonstrate:
- Data-driven problem solving
- Model selection and evaluation
- Insight generation for business decisions


