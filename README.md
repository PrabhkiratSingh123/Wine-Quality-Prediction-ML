# Wine-Quality-Prediction-ML
Machine learning–based wine quality classification using ensemble models, featuring White vs Red wine comparison, feature importance analysis, and statistical validation.
# 🍷 Wine Quality Prediction using Machine Learning

### *Comparative Analysis of White and Red Wine Datasets*

## 📌 Project Overview

This project focuses on predicting wine quality using **advanced ensemble-based machine learning models**. The study analyzes both **White and Red wine datasets** from the **UCI Machine Learning Repository** and classifies wine quality into **Low, Medium, and High** categories based on physicochemical properties.

The objective is to evaluate multiple predictive models, compare their performance, and identify the most effective algorithm for wine quality classification.
---

## 📊 Dataset

* **Source:** UCI Machine Learning Repository
* **Link:** [https://archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality)
* **Wine Types:** White Wine & Red Wine
* **Features:** 11 physicochemical attributes
* **Target Variable:** Wine Quality (Categorized into Low, Medium, High)

---
## ⚙️ Methodology

1. **Data Preprocessing**

   * Quality score transformed into categorical labels
   * Feature scaling using StandardScaler
   * Stratified train-test split for balanced evaluation

2. **Exploratory Data Analysis**

   * Correlation heatmaps
   * Quality distribution analysis
   * Alcohol and acidity impact visualization
   * White vs Red wine comparison


3. **Model Development**
   The following ensemble learning models were trained and evaluated:

   * Random Forest
   * Gradient Boosting
   * XGBoost
   * LightGBM
   * CatBoost

4. **Model Evaluation**

   * Accuracy score
   * Confusion matrix
   * Classification report
   * Model ranking
   * Statistical comparison (paired t-test & variance analysis)

---



## 📈 Key Visualizations

* Model accuracy comparison bar charts
* Confusion matrices for each model
* Feature importance plots
* Correlation heatmaps
* White vs Red wine comparative analysis

---
## 🏆 Results Summary

* **CatBoost** achieved the highest classification accuracy for both White and Red wine datasets.
* **White wine models** showed more stable performance compared to Red wine models.
* **Alcohol content**, **volatile acidity**, **sulphates**, and **chlorides** were identified as the most influential features affecting wine quality.
* Statistical testing confirmed performance differences between datasets.

---
## 🧠 Key Learnings

* Ensemble learning significantly improves multi-class classification performance.
* Feature engineering and correct target encoding are critical for reliable predictions.
* CatBoost effectively handles nonlinear relationships in structured chemical data.
* Statistical validation strengthens confidence in model comparisons.
* Dataset characteristics strongly influence model stability and accuracy.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas, numpy
  * matplotlib, seaborn
  * scikit-learn
  * XGBoost
  * LightGBM
  * CatBoost

---

## 🚀 Future Enhancements

* Hyperparameter optimization (Grid Search / Bayesian Optimization)
* Deep learning-based wine quality prediction
* Web-based model deployment using Flask or Streamlit
* Integration of sensory and environmental data

---

## 🔗 Links

* **Dataset:** [https://archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality)
* **LinkedIn:** [](https://www.linkedin.com/feed/update/urn:li:activity:7405210251966414848/))*

