# 🌍 Global Terrorism Analysis & Risk Clustering

## 📌 Project Overview

This project performs a comprehensive analysis of global terrorism data using **Exploratory Data Analysis (EDA)** and **Unsupervised Machine Learning** techniques. The goal is to uncover hidden patterns, understand trends, and classify countries based on the severity of terrorist activities.

The project integrates **Python-based analysis** with an **interactive Power BI dashboard** to present insights in a clear and actionable format.
![Machine Learning Process](https://github.com/RAVINDRA-robi/Global-Terrorism-Analysis---Exploratory-Data-Analysis-EDA-with-ML-/blob/main/PROJECT%20MODEL%20WORKFLOW.png)
---

## 🎯 Objectives

* Analyze global terrorism trends across countries and years
* Identify the most affected regions and peak activity periods
* Explore patterns in attack types, weapons, and casualties
* Reduce data dimensionality using **PCA**
* Cluster countries into risk categories using **K-Means**
* Build an interactive dashboard for visual storytelling

---

## 📂 Dataset Description

The dataset contains detailed records of terrorist incidents, including:

* `iyear` → Year of incident
* `country_txt` → Country name
* `attacktype1_txt` → Type of attack
* `weaptype1_txt` → Weapon used
* `nkill` → Number of people killed
* `nwound` → Number of people wounded

---

## 🛠️ Tech Stack

### 🔹 Data Analysis & ML

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

### 🔹 Machine Learning Techniques

* Standardization (StandardScaler)
* PCA (Dimensionality Reduction)
* K-Means Clustering

### 🔹 Visualization

* Power BI Dashboard

---

## 🔄 Project Workflow

```
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis (EDA)
   ↓
Feature Engineering (Attack Count, Casualties)
   ↓
Data Scaling (StandardScaler)
   ↓
Dimensionality Reduction (PCA)
   ↓
Clustering (K-Means)
   ↓
Risk Level Classification
   ↓
Dashboard Visualization (Power BI)
```

---

## 📊 Exploratory Data Analysis

Key analyses performed:

* Trend of attacks over time
* Top affected countries
* Most used weapon types
* Year-wise casualties
* Correlation between kills and wounds

These analyses help in understanding the **structure and distribution** of the dataset before applying machine learning.

---

## 🤖 Machine Learning Implementation

### 🔹 Feature Selection

The following features were used for clustering:

* Total attacks per country
* Total number of killed
* Total number of wounded

---

### 🔹 PCA (Principal Component Analysis)

* Reduced features from 3 → 2 dimensions
* Improved visualization and clustering performance

---

### 🔹 K-Means Clustering

* Optimal clusters determined using Elbow Method
* Final model: **K = 3**

Cluster labels mapped to:

* Low Risk
* Medium Risk
* High Risk

---

## 📈 Key Insights

* **Most affected country:** El Salvador
* **Peak year of attacks:** 1980
* **Most common weapon:** Explosives
* **Total killed:** 19,367
* **Total wounded:** 16,290
* **Correlation (kills vs wounds):** 0.2 (weak relationship)

### 📊 Cluster Distribution

* Low Risk → Majority of countries
* Medium Risk → Moderate number
* High Risk → Very few countries

---

## 📊 Power BI Dashboard

The dashboard provides an interactive view of the analysis with:

* KPI Cards (Total incidents, killed, wounded)
* Time series analysis (Attacks over years)
* Geographic distribution (Map visualization)
* Top countries and attack types
* Severity classification
* Scatter plot (Killed vs Wounded)

---

## 🧾 Conclusion

This project successfully combines **EDA and unsupervised machine learning** to extract meaningful insights from global terrorism data. The clustering approach helps categorize countries based on risk levels, while the Power BI dashboard enables intuitive exploration of trends and patterns.

The results can support **data-driven understanding and strategic analysis** of global terrorism activities.

---

---

## 🔗 Project Link

Add your GitHub repository link here
