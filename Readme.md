
# 🦈 Shark Tank India Analysis

## 📌 Overview

This project presents an **in-depth analysis** of the *Shark Tank India* startups dataset using **Python in Jupyter Notebook**.
The aim was to understand **industry distributions, funding patterns, investment behavior of sharks, startup revenues**, and test hypotheses regarding **funded vs bootstrapped startups**.

### 📂 Dataset Source

Dataset: [`Shark Tank India` by thirumani](https://www.kaggle.com/datasets/thirumani/shark-tank-india)

---

## 🔧 Tech Stack & Tools

* **Python**
* **Jupyter Notebook**
* **Libraries:**

  * `pandas` → Data Cleaning
  * `numpy` → Numerical Computation
  * `matplotlib` & `seaborn` → Data Visualization
  * `statsmodel` → Hypothesis Testing

---

## 📊 Analysis Workflow

### 1. Data Cleaning 🧹

* Removed nulls & duplicates
* Standardized column names
* Fixed categorical variables (Bootstrapped, Funded, Unknown)
* Converted datatypes for numerical consistency

---

### 2. Exploratory Data Analysis (EDA) 🔍

#### **Univariate Analysis**

* Industry-wise startup distribution (**Pie chart**)
* Bootstrapped vs Funded startup categorization (**Donut chart**)
* State-wise startup participation (**Bar chart**)
* Distribution of original ask amounts

#### **Bivariate Analysis**

* Revenue vs Startup comparisons
* Old vs Expected yearly revenue
* Investments made by each shark

#### **Multivariate Analysis**

* Cross-analysis of industry, funding type, and offers
* **Correlation heatmap** for numerical features

---

## 📈 Visual Insights

* **Industry Trends:** Food & Beverage and Beauty/Fashion dominate the startup landscape.
* **Funding Type:** Majority of accepted offers are from startups with **Unknown funding status**, while Funded and Bootstrapped startups show similar acceptance proportions.
* **Revenue:** Clear differences between reported yearly revenue and expected future revenue among startups.
* **Investor Behavior:** Sharks like **Aman, Peyush, and Namita** emerged as top investors across all seasons.
* **State-wise Distribution:** Maharashtra, Delhi, and Karnataka lead in number of startups.
* **Correlation Heatmap:** Showed relationships between investment, revenue, and ask amount — highlighting which financial metrics move together.

---

## 📑 Hypothesis Testing

* **Proportion Z-test**
* **Objective:** To check if funded startups had significantly higher offer acceptance than bootstrapped startups.
* **Result:** Failed to reject H₀ → No statistically significant difference observed.

---

## ✅ Conclusion

* Funded startups appear stronger in absolute numbers, but **acceptance rate differences are not statistically significant**.
* Industry & geography strongly influence participation.
* Sharks show **individual investment preferences** that affect deal distribution.
* Correlation analysis provided insights into how **revenue, investments, and ask amounts** relate.

