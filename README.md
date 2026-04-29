# 🪔 Diwali Sales Analysis — Customer Behavior & Revenue Insights

> **Exploratory Data Analysis (EDA) on festive season retail data to uncover high-value customer segments and drive data-backed business decisions.**

---

## 📌 Project Overview

India's Diwali season is one of the largest retail events in the world. This project dives deep into transactional sales data to answer a critical business question:

> *Who is actually buying, and what are they buying?*

By profiling customers across gender, age, location, occupation, and marital status — and correlating those profiles with product preferences and spending — this analysis surfaces actionable insights that can directly inform marketing strategy, inventory planning, and targeted campaigns.



## 🎯 Business Problem

Retailers run blanket Diwali campaigns, but not all customer segments respond equally. Without understanding **who spends the most** and **on what**, marketing budgets get wasted. This analysis identifies the highest-value customer cohort so businesses can target precisely and convert more.



## 🔍 Key Insights Uncovered

| Dimension | Finding |
| 👩 **Gender** | Female buyers dominate both in volume and purchasing power |
| 🎂 **Age Group** | Women aged **26–35** are the highest-spending segment |
| 🗺️ **Geography** | Top revenue states: **Uttar Pradesh, Maharashtra, Karnataka** |
| 💍 **Marital Status** | Married women show significantly higher spend than other groups |
| 💼 **Occupation** | Buyers from **IT, Healthcare & Aviation** sectors spend the most |
| 🛒 **Product Category** | **Food, Clothing & Electronics** are the top revenue-generating categories |

### ✅ Final Business Insight
> *Married women aged 26–35 from UP, Maharashtra & Karnataka — working in IT, Healthcare, or Aviation — are the most likely to purchase Food, Clothing, and Electronics during Diwali.*

This customer persona is the **primary target segment** for festive season campaigns.


## 🛠️ Tech Stack

| Tool | Purpose |
| **Python 3** | Core programming language |
| **Pandas** | Data loading, cleaning & transformation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Base visualizations |
| **Seaborn** | Statistical plotting & styled bar charts |
| **Jupyter Notebook** | Interactive analysis environment |



## 📂 Project Structure

📦 Diwali-Sales-Analysis
 ┣ 📓 Diwali_Sales_Analysis.ipynb   # Main analysis notebook
 ┣ 📊 Diwali Sales Data.csv         # Raw dataset
 ┗ 📄 README.md



## ⚙️ Data Pipeline

Raw CSV  →  Data Cleaning  →  Feature Engineering  →  EDA  →  Insights

**Cleaning steps performed:**
- Dropped irrelevant/blank columns (`Status`, `unnamed1`)
- Handled null values via row removal
- Type-cast `Amount` column to integer for accurate aggregation

---

 📊 Analysis Breakdown

 1. Gender Analysis
- Count distribution of buyers by gender
- Total revenue contribution by gender

 2. Age Group Analysis
- Purchase frequency segmented by age group and gender
- Revenue comparison across age buckets

 3. State-wise Analysis
- Top 10 states by order volume
- Top 10 states by total revenue

 4. Marital Status Analysis
- Buyer count by marital status
- Spending pattern split by marital status × gender

 5. Occupation Analysis
- Order count across industries
- Revenue contribution by occupational sector

6. Product Category Analysis
- Top-selling product categories by volume
- Top 10 highest-revenue categories
- Top 10 best-selling individual Product IDs

## How to Run
# 1. Clone the repository
git clone https://github.com/your-username/Diwali-Sales-Analysis.git
cd Diwali-Sales-Analysis

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook Diwali_Sales_Analysis.ipynb

 💡 Skills Demonstrated

Exploratory Data Analysis (EDA)** — end-to-end structured analysis workflow
Data Wrangling** — handling nulls, type casting, column drops
Customer Segmentation** — multi-dimensional profiling for business targeting
Data Visualization** — clear, insight-driven charts using Seaborn & Matplotlib
Business Storytelling** — translating raw data into a concrete, actionable persona


 📈 Sample Visualizations

> Charts generated in the notebook include gender vs. revenue bar plots, age group purchase frequency with gender hue, state-wise order & revenue rankings, and product category revenue breakdowns.

 🤝 Connect

If you found this project insightful or want to discuss the analysis, feel free to reach out!

www.linkedin.com/in/ishikasutradhar
