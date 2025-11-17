# 🛒 Amazon E-Commerce Product Analysis – Python EDA

### **Uncovering Pricing, Ratings, Discounts & Category Trends | By Vishal Ratnakar**

<p align="center">
  <img src="https://img.shields.io/badge/Skills-Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Seaborn%20%7C%20Matplotlib-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-EDA%20%7C%20Pricing%20Insights%20%7C%20Category%20Trends-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-E--Commerce-purple?style=for-the-badge" />
</p>

---

## 📌 **Project Overview**

This project performs Exploratory Data Analysis on **1,465 Amazon e-commerce products** to uncover trends across pricing, ratings, reviews, discounts, and categories.
The objective is to help product managers and category leaders identify **top-performing products**, **high-value categories**, and **pricing–rating relationships** to optimize promotions and sales strategies.

### 🔥 Key Capabilities

* Full **data cleaning & preprocessing**
* Feature engineering for deeper insights
* Category-level performance analysis
* Statistical testing (Chi-Square)
* Visual storytelling with Python

---

## 🗂 **Dataset Overview**

**File:** `amazon_eda_python.csv`
**Size:** 1,465 rows × 16 columns

### Contains:

* Product name & description
* Category
* Raw & discounted price
* Discount percentage
* Ratings
* Number of reviews
* Product link & image URL

---

## 🧼 **Data Cleaning & Preprocessing**

✔ Handled missing values
✔ Converted price, discount, & rating fields into numeric
✔ Removed invalid rows and duplicates

### 🛠 Feature Engineering

Generated analytical fields:

* **`discount_amount`** → Original price – Discounted price
* **`rating_level`** → Categorized ratings into Low / Medium / High
* **`price_bin_quantile`** → Price distribution bins for statistical analysis

---

## 📊 **Exploratory Analysis & Visualizations**

### **1️⃣ Category-Level Insights**

* Top 10 categories by product count
* Avg ratings by category
* Price variation across categories

📌 Top Performing Categories:

* USB Cables
* Smartwatches
* Smartphones
* Smart TVs
* In-ear Headphones

---

### **2️⃣ Rating Distribution**

Visualization includes:

* Histogram of rating distribution
* Boxplot to detect rating outliers

Insights:

* Majority of products have **ratings ≥ 4.0**
* Low-rated products often belong to niche categories

---

### **3️⃣ Price vs Rating Relationship**

Scatter + regression trend visualization.

Key Finding:

* **Higher-priced products tend to have better ratings**
* Statistical testing reinforces this

---

### **4️⃣ Discount % vs Rating**

* Smartwatches show **~70% average discount**
* Smartphones rely less on discounts
* No strong direct correlation between discount % and ratings

---

### **5️⃣ Discount Distribution**

Distribution plot of % discount across the dataset.

Insights:

* Large cluster of products around 40–50% discount
* Few extreme discounts beyond 70%

---

## 📐 **Statistical Analysis**

### **Chi-Square Test: Price Bin vs Rating Level**

* **p-value: 0.0189** → Statistically significant
  📌 High-priced products are **more likely** to have higher ratings.

---

## 🔦 **Highlight Products**

### ⭐ High Review Volume Products

* AmazonBasics HDMI Cable → **426K+ reviews**, avg rating 4.4
* boAt Wireless Headphones
* Instant Pot Air Fryer

### 🔍 Outliers Identified

* Premium devices priced **above ₹77,000**
* Products with **400,000+ reviews**

---

## 🚀 **Technologies Used**

* **Python**
* **Pandas** → Data cleaning
* **NumPy** → Feature engineering
* **Matplotlib & Seaborn** → Visual insights
* **Jupyter Notebook** → Analysis & reporting

---

## 📦 **Deliverables**

```
├── amazon_eda_python.csv        # Raw dataset
├── amazon_ecom_cleaned.csv      # Cleaned dataset
├── amazon_eda_report.md         # Analysis report
├── amazon_eda.ipynb             # Jupyter Notebook (EDA code)
└── README.md                    # This file
```

---

## 📈 **Business Impact**

This EDA enables Amazon category managers to:

* Identify **high-value categories**
* Adjust **pricing strategies** based on competitive insights
* Optimize **discounts & promotions**
* Prioritize **products with high customer appeal**
* Detect outliers and quality issues
* Make data-driven category expansion decisions

---

## 👨‍💻 **Author**

**Vishal Ratnakar**
Data Analyst | Python Developer | E-Commerce Insights | Visualization Specialist

---

## ⭐ **If you found this project helpful, please consider starring the repository!**
✔ A short **resume-ready summary** for this project
Just tell me!
