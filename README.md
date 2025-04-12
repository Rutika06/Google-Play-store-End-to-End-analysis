# 📊 Google Play Store End-to-End Data Analysis

This project explores the Google Play Store dataset to extract meaningful insights related to app ratings, installs, pricing strategies, and categories. It covers everything from data cleaning to insightful visualizations and business question analysis.

---

## 🧠 Overview

The goal is to understand the dynamics of the Google Play ecosystem using statistical and visual methods. The analysis includes:

- Data preprocessing (cleaning, transforming, outlier handling)
- Univariate and bivariate analysis
- Answering real-world business questions
- Drawing conclusions relevant to app developers and businesses

---

## 📁 Dataset Information

**Key Columns:**
- `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`
- `Type`, `Price`, `Content Rating`, `Genres`
- `Last Updated`, `Current Version`, `Android Version`

**Key Transformations:**
- Converted `Price`, `Installs`, and `Last Updated` to appropriate data types
- Handled missing values using `median` and `mode`
- Removed duplicate entries
- Capped outliers using percentiles

---

## 🧼 Data Cleaning

- Missing value imputation
- Duplicate removal
- Data type conversions
- Outlier treatment

---

## 📊 Analysis Performed

### ✅ Univariate Analysis
- App ratings distribution
- Pricing and install trends
- Most frequent categories

### 🔗 Bivariate Analysis
- Installs vs Ratings
- Price vs Rating
- Free vs Paid app comparisons

### 📈 Visualizations
- Bar plots
- Histograms
- Scatter plots
- Box plots

---

## ❓ Business Questions Answered

- What is the average app rating?
- What percentage of apps are free vs paid?
- What is the most common app category?
- Which category has the highest number of apps?
- How are app prices distributed?
- Do free apps have better ratings than paid apps?
- Which categories have the highest average ratings?
- Does a higher number of installs correlate with higher ratings?
- Do paid apps generate more installs than free apps?
- Which categories have the most paid apps?

---

## 🛠️ How to Use

1. Clone this repository.
2. Open `GooglePlayStore_Project.ipynb` using Jupyter Notebook.
3. Run each cell to perform cleaning, transformation, analysis, and visualization.
4. Customize filters and graphs to explore other insights.

---

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn
