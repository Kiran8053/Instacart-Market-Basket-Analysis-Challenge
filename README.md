# Instacart Market Basket Analysis

## Overview
This project analyzes *Instacart's customer purchase patterns* to uncover actionable insights for cross-selling, marketing campaigns, and customer segmentation.  
Using *Exploratory Data Analysis (EDA), **Principal Component Analysis (PCA), **K-Means Clustering, and **Association Rule Mining (Apriori)*, the project provides data-driven strategies for improving customer engagement.

---

## Objectives
- Segment customers based on purchasing behavior.
- Identify frequently bought-together items for cross-selling.
- Derive data-driven marketing recommendations.

---

## Repository Structure

Instacart-Market-Basket-Analysis/
│── data/ # CSV dataset files
│ ├── order_products__train.csv
│ ├── products.csv
│── notebooks/ # Jupyter notebooks
│ ├── Instacart-Simple-Data-Exploration.ipynb
│ ├── Customer-Segments-with-PCA.ipynb
│ ├── Association-Rule-Mining.ipynb
│── README.md # Project documentation
│── requirements.txt # Python dependencies

## Tech Stack
- *Languages:* Python (3.x)
- *Libraries:* Pandas, NumPy, Matplotlib, Scikit-learn, Mlxtend
- *Tools:* Jupyter Notebook, GitHub

---

## Key Steps & Methodology
### 1. Data Exploration
- Checked data quality and missing values.
- Merged multiple CSV tables for complete analysis.
- Explored distribution of orders, products, and aisles.

### 2. Customer Segmentation (Unsupervised Learning)
- Applied *PCA* for dimensionality reduction.
- Implemented *K-Means clustering* to group customers by purchase behavior.
- Visualized clusters to understand purchasing patterns.

### 3. Association Rule Mining
- Used the *Apriori Algorithm* to find frequent item sets.
- Generated rules with *Support, Confidence, and Lift* metrics.
- Identified product pairs/trios for cross-selling opportunities.

---

## Results & Insights
- *Top Purchased Products:* Identified the most common items in baskets.
- *Customer Segments:* Found clear segments with distinct buying behaviors.
- *Product Associations:* Discovered product combinations often purchased together (e.g., "Bananas" + "Organic Whole Milk").
