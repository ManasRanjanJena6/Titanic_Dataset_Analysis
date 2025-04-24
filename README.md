# 🚢 Titanic Data Preprocessing Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

This project focuses on preprocessing the Titanic dataset for further analysis or model building. The key steps include cleaning, encoding, normalizing, and outlier handling to prepare the data for machine learning or data visualization.

## 🔍 Dataset

**Dataset Name:** `Titanic-Dataset.csv`  
This dataset contains passenger details such as age, sex, fare, class, survival status, etc., from the historic Titanic shipwreck.

---

## ✅ Tasks Performed

### 1. 📥 Import and Explore Dataset
- Loaded the dataset using `pandas`.
- Explored data types, basic statistics, and identified missing values.

### 2. 🧹 Handle Missing Values
- Filled numerical missing values with **mean**.
- Filled categorical missing values with **mode**.

### 3. 🧠 Encode Categorical Features
- Used **Label Encoding** to convert string categories into numerical values for machine learning compatibility.

### 4. 📏 Normalize Numerical Features
- Applied **StandardScaler** from `sklearn` to standardize numerical columns for uniform scale.

### 5. 📦 Visualize and Remove Outliers
- Used **boxplots** to visualize outliers.
- Removed outliers using the **Interquartile Range (IQR)** method for cleaner data.

---

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn.preprocessing`

---

## 📁 Output

After preprocessing:
- Dataset is clean, encoded, and scaled.
- Outliers have been removed.
- Ready for exploratory data analysis (EDA) or machine learning.

---

## 💡 Next Steps (Suggestions)
- Perform survival analysis using logistic regression or decision trees.
- Build classification models and evaluate accuracy.
- Visualize key insights like survival rate by gender or class.

---

## 🧠 Author

Developed by Manas Ranjan Jena

Feel free to ⭐️ this project if you find it helpful!
