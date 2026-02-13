# Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset as part of an AI & ML Internship Task.

The objective of this task is to understand the dataset using statistical analysis and visualizations, identify patterns, trends, and anomalies, and make feature-level inferences before applying machine learning models.

---

## 🎯 Objectives

1. Generate summary statistics (mean, median, standard deviation, etc.)
2. Create histograms and boxplots for numeric features
3. Use pairplot and correlation matrix for feature relationships
4. Identify patterns, trends, and anomalies in the dataset
5. Make basic feature-level inferences from visualizations

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📂 Dataset Information

- Dataset: Titanic Dataset
- Total Records: 891
- Total Features: 12
- Target Variable: `Survived`

Key Features:
- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

---

## 🔎 Steps Performed

### 1️⃣ Summary Statistics
- Used `.describe()` to calculate mean, std, min, max, etc.
- Calculated median separately.
- Identified missing values using `.isnull().sum()`
- Observed that:
  - Age has missing values
  - Cabin has more than 75% missing values
  - Fare contains large variance

---

### 2️⃣ Distribution Analysis
- Created histograms for numeric features.
- Created boxplots for Age and Fare.
- Observed:
  - Fare is highly right-skewed.
  - Extreme outliers present in Fare.
  - Age is moderately distributed with some missing values.

---

### 3️⃣ Feature Relationship Analysis
- Created correlation heatmap.
- Used pairplot to analyze relationships with survival.
- Observed:
  - Pclass negatively correlated with Fare.
  - Fare positively related to survival.
  - SibSp and Parch moderately correlated.

---

### 4️⃣ Patterns & Trends Identified

- Females had significantly higher survival rates than males.
- 1st class passengers survived more compared to 3rd class.
- Passengers who paid higher fare had better survival chances.
- Children showed relatively better survival than adult males.

---

### 5️⃣ Anomalies Identified

- Fare contains extreme high-value outliers.
- Cabin has excessive missing values.
- Age contains missing values requiring imputation.
- Fare shows strong positive skewness.

---

## 📊 Key Insights

- Gender is the strongest predictor of survival.
- Passenger class significantly impacts survival probability.
- Socio-economic status influenced survival outcomes.
- Data preprocessing (handling missing values and outliers) is required before modeling.

---

## 🧠 What I Learned

- Importance of EDA before building ML models.
- How visualization helps identify patterns and anomalies.
- Detecting skewness and correlation.
- Making feature-level inferences from visual analysis.

---

## 🚀 How to Run This Project

1. Clone the repository:
