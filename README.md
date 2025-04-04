# Insurance-Cost-Analysis
# 💰 Medical Insurance Cost Analysis – Python Project

This project focuses on analyzing and modeling **medical insurance costs** using Python, with the goal of identifying key factors that influence insurance premiums and predicting individual expenses.

## 📊 Project Overview

The dataset includes demographic and health-related attributes such as age, sex, BMI, number of children, smoking status, and region. This project performs exploratory data analysis (EDA), statistical modeling, and cost prediction using regression algorithms.

## ✅ Key Objectives

- Analyze relationships between patient characteristics and insurance charges
- Identify key cost-driving factors (e.g., smoking, BMI, age)
- Build predictive models to estimate insurance charges
- Visualize trends and correlations through interactive plots

## 🛠 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook** for interactive coding and reporting
- **Statistical Techniques**: Linear Regression, Correlation Analysis, Feature Engineering

## 📁 Dataset

- Source: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- 1,300+ records with features:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

## 📈 Key Insights

- **Smoking** has the largest impact on cost, increasing premiums significantly
- **BMI** and **age** are strong cost predictors with a positive linear relationship
- **Smokers with high BMI** are the most expensive demographic group
- Regression model achieved good performance (R² score ~0.75 on test data)

## 🔮 Model Performance

- **Train/Test Split**: 80/20
- **Best Model**: Multiple Linear Regression
- **R² Score**: 0.75
- **MAE**: ~$4,200

## 📌 Status

The analysis is complete and provides a strong foundation for further work such as feature expansion, regularization, or deployment via a simple Flask app or dashboard.

---

