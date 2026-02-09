# 🎆 Diwali Sales Analysis (Python + Pandas)

A complete end-to-end **Data Analysis Project** performed using **Python, Pandas, Matplotlib, and Seaborn** to understand customer purchasing behavior during the Diwali festive season. This project includes data cleaning, transformation, exploratory data analysis (EDA), and visualization of valuable business insights.

---

## 📌 Project Overview

The **Diwali Sales Analysis** project focuses on analyzing festival-time sales patterns to help businesses:

* Identify top-performing states
* Understand customer demographics
* Analyze product categories & purchasing trends
* Improve marketing strategies
* Boost festive sales performance

The insights extracted from this dataset mimic real corporate analytics workflows used by retail & e‑commerce companies.

---

## 🧰 Tools & Technologies Used

* **Python**
* **Pandas** for data cleaning & manipulation
* **NumPy**
* **Matplotlib & Seaborn** for data visualization
* **Jupyter Notebook** for analysis & reporting

---

## 📂 Project Structure

```
📁 Diwali-Sales-Analysis
│
├── 📄 Diwali Sales Data.csv
└── 📄 README.md
├── 📄 diwali_sales_analysis.ipynb
```

---

## 🔧 Steps Performed

### **1. Data Cleaning**

* Removed null/blank entries
* Dropped unnecessary columns such as `Status` & `unnamed1`
* Converted data types for analysis
* Cleaned categorical values

### **2. Exploratory Data Analysis (EDA)**

Key analysis includes:

* **Gender-wise spending behavior**
* **Age group distribution of buyers**
* **State-wise total sales**
* **Occupation-wise purchasing trends**
* **Marital status impact on spending**
* **Top product categories and top-selling items**

### **3. Data Visualization**

Used bar charts, count plots, histograms, and category plots to reveal patterns such as:

* Women contributed more to total sales compared to men
* Most buyers are from the **26–35 age group**
* **Uttar Pradesh, Maharashtra, and Karnataka** are top revenue-generating states
* Married women are the highest spenders
* The **Food**, **Clothing**, and **Electronics** categories dominate festival sales

---

## 📊 Key Insights

### 🔹 **Top Performing States**

High sales observed from:

* Uttar Pradesh
* Maharashtra
* Karnataka

### 🔹 **Customer Demographics**

* Majority buyers: **Female, age 26–35**
* Highest spending group: **Married Women**

### 🔹 **Occupation Trends**

Most purchasers are from:

* IT Sector
* Healthcare
* Aviation

### 🔹 **Product Preferences**

Top categories during Diwali:

* Clothing
* Food
* Electronics

---

## 🧪 Sample Code Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')

# Cleaning
df.drop(['Status', 'unnamed1'], axis=1, inplace=True)
df.dropna(inplace=True)

# Visualization
sns.countplot(data=df, x='Gender')
plt.show()
```

---

## 🚀 What I Learned

* Real-world data cleaning using Pandas
* Handling categorical data
* Extracting business insights from raw data
* Creating meaningful visual storytelling through charts
* Understanding consumer behavior in festive seasons

---

## 📬 Contact

**Shiva – Data Analyst**

📧 Email: *[(mailto:shivakumar110045@gmail.com)*

🐙 GitHub: * https://github.com/shiva-singh01 *

---

### ⭐ If you like this project, feel free to star the repository!
