📊 Google Play Store End-to-End Data Analysis
Uncovering insights from app ratings, pricing, installs, and more

🧠 Overview
In a world driven by mobile apps, understanding the dynamics of the app marketplace is crucial. This project dives deep into the Google Play Store dataset, analyzing various features to uncover patterns in app ratings, pricing, installs, and categories.

From data cleaning to visualization, this end-to-end analysis not only prepares the dataset for exploration but also provides valuable business insights for developers, marketers, and stakeholders in the app ecosystem.

🔧 Features of the Project
📌 Data Cleaning
Converted data types (e.g., Price, Installs, Last Updated) to appropriate formats.

Replaced missing values using median and mode strategies.

Removed duplicate entries to ensure data quality.

Treated outliers using percentile capping for robust analysis.

📊 Univariate Analysis
Analyzed single variables like:

App Ratings

Pricing Distribution

Most Common Categories

🔗 Bivariate Analysis
Explored relationships between:

Installs vs. Ratings

Ratings vs. Price

Free vs. Paid app performance

📈 Visualizations
Utilized bar charts, histograms, scatter plots, and box plots to bring data to life and enhance interpretability.

📁 Dataset Information
Key Columns:
App Name, Category, Rating, Reviews, Size, Installs

Type (Free/Paid), Price, Content Rating, Genres

Last Updated, Current Version, Android Version

Transformations Applied:
Data type conversion for numeric and date columns.

Missing values filled using meaningful strategies.

Duplicates dropped for cleaner data.

Outliers capped to reduce noise and skew.

❓ Business Questions Explored
This analysis answers several crucial business and product strategy questions, such as:

💬 What is the average app rating on the Play Store?

💰 What percentage of apps are free vs. paid?

📂 What is the most common app category?

📈 Which categories have the highest number of apps?

🧾 How are app prices distributed?

⭐ Do free apps have better ratings than paid apps?

🏆 Which categories have the highest average ratings?

🔄 Does a higher number of installs mean better ratings?

📉 Do paid apps get more installs than free apps?

🗃️ Which categories contain the most paid apps?

🧪 How to Use This Project
Open the Jupyter Notebook: GooglePlayStore_Project.ipynb.

Run the cells in sequence to perform:

Data cleaning

Data transformation

Visualization and analysis

Feel free to tweak the filters and explore custom insights based on your own questions!

🛠️ Requirements
To run this project smoothly, make sure you have the following Python libraries installed:

pandas

numpy

matplotlib

seaborn

💡 Insights & Business Impact
This project offers data-driven recommendations and perspectives that can shape app development strategies:

📱 User Preference: Most users prefer free apps — pricing influences adoption.

🎯 Category Popularity: Knowing which categories are over or under-saturated can guide developers.

🧮 Install Patterns: Free apps tend to attract more downloads; however, paid apps often have niche but loyal users.

💬 Rating Trends: Free apps sometimes score lower — possibly due to ads or limited features.

🔗 Project Links
📂 GitHub Repository: [Add your GitHub link here]

▶️ YouTube Walkthrough: [Add your YouTube video link here]

This project is a great step toward mastering real-world data analysis and delivering insights that matter. Whether you’re an aspiring data scientist or a developer curious about app store trends — this analysis gives you a strong foundation.

Let me know if you'd like a version tailored for Medium formatting with proper headings, bold/italic styles, and embedded links!



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
2. Open the file using Jupyter Notebook.
3. Run each cell to perform cleaning, transformation, analysis, and visualization.
4. Customize filters and graphs to explore other insights.

---

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn

💡 Key Insights
Majority of the apps are free, and they attract more installs.

Categories like Games and Tools dominate the store.

Free apps generally receive more reviews but slightly lower ratings.

Paid apps are less common but may cater to niche markets.

