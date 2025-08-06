# 🛒 Walmart Sales Data Analysis Project

## 📌 Project Overview

This project presents an **end-to-end data analytics case study** on Walmart sales data. The objective was to explore the data using Python, solve key business problems with SQL in PostgreSQL, validate assumptions through hypothesis testing, and deliver a final interactive dashboard using Power BI.

---

## 🧰 Tools & Technologies Used

| Tool / Language | Purpose |
|------------------|---------|
| **Python (Pandas, Seaborn, Matplotlib)** | Exploratory Data Analysis (EDA) |
| **PostgreSQL (pgAdmin/Server)** | Solving business queries using SQL |
| **Power BI** | Final interactive report and visual storytelling |
| **Scipy & Statsmodels** | T-test & Q-Q plots for hypothesis testing |

---

## 🎯 Project Objectives

- Clean and explore Walmart sales data using Python
- Solve real-world business questions using SQL in PostgreSQL
- Validate assumptions using statistical hypothesis testing (T-test)
- Create an executive dashboard in Power BI to present insights

---


---

## 🔍 Exploratory Data Analysis (Python)

Performed univariate and bivariate analysis to:

- Understand sales trends across branches and product lines
- Analyze transaction volume and revenue by city and time
- Visualize customer ratings and profit distribution
- Prepare data for statistical testing and BI integration

---

## 🧾 Business Problem Solving (PostgreSQL)

Solved key business questions like:

- 🔝 Which product line has the highest average rating per city?
- 💳 What is the most common payment method used in each branch?
- 📆 Identify the busiest day and hour for each branch
- 📉 List the 5 branches with the highest revenue drop YoY
- 🕒 Segment sales into morning, afternoon, and evening to find peak hours

> ✅ All SQL queries were written and executed on a **PostgreSQL server** using **pgAdmin**

---

## 📊 Hypothesis Testing (T-Test: Profit Margin by Payment Method)

### 🎯 Objective

Determine whether profit margins differ significantly between two specific payment methods (e.g., *Cash* vs *E-wallet*)

### 🧪 Statistical Setup

- **Null Hypothesis (H₀):**  
  No significant difference in average profit margins between the two payment methods

- **Alternative Hypothesis (H₁):**  
  A significant difference exists in average profit margins between the two payment methods

### 🧠 Methodology

- **Test Type:** Independent Two-Sample **T-Test** (Welch’s T-test for unequal variances)
- **Normality Check:**  
  Used **Q-Q plots** and **Shapiro-Wilk test** to verify normal distribution of profit margins
- **Assumptions Checked:**  
  - Independent groups ✅  
  - Normality ✅  
  - Unequal variance allowed ✅

### ✅ Result

> The **p-value was less than 0.05**, so the null hypothesis was **rejected**.  
> Conclusion: There is a **statistically significant difference** in profit margins between *E-wallet* and *Cash* payments, with *E-wallet* showing slightly higher margins.

---

## 📈 Power BI Dashboard

An interactive, multi-page dashboard summarizing all key findings.

### 📌 Page 1: Sales Overview
- Total Revenue, Avg Rating, Gross Income, Total Transactions
- Revenue breakdown by Branch and Product Category

### 📊 Page 2: Trends and Timing
- Month-on-Month revenue trends
- Hourly sales patterns across branches
- Weekday vs Weekend performance

### 🔍 Page 3: Deep Dive Insights
- Ratings by branch and product line
- Payment method usage
- Time-of-day segmentation (Morning, Afternoon, Evening)
- Branches with highest YoY revenue drops

---

## 💡 Key Insights

- Branch 

---

## 🧠 Learnings

- Hands-on experience integrating Python, SQL, statistics, and BI
- Gained practical understanding of exploratory data analysis and visual storytelling
- Applied T-tests to validate real-world business assumptions
- Improved dashboard design using DAX and Power BI features

---



