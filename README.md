# 📊 Superstore Data Analysis: Sales, Profit & Regional Insights

## 📌 Project Overview

This project performs a comprehensive data analysis on the **Superstore Dataset** using Python and Pandas. The goal is to uncover key business insights about sales performance, profitability, regional trends, customer segments, and seasonal patterns to provide **data-driven recommendations**.

---

## 🎯 Objective

- Identify the most profitable product category
- Determine the least performing region
- Analyze the relationship between sales and profit
- Detect seasonal sales patterns
- Find loss-making sub-categories
- Provide actionable business recommendations

---

## 📊 Dataset

| Property | Details |
|----------|---------|
| **Source** | Kaggle (vivek468/superstore-dataset-final) |
| **Rows** | 9,986 |
| **Columns** | 21 |
| **Time Period** | 2014 - 2017 |
| **File Size** | 2.29 MB |

### Key Columns
- `Order Date`, `Ship Date` - Time-based analysis
- `Category`, `Sub-Category`, `Product Name` - Product hierarchy
- `Sales`, `Profit`, `Discount`, `Quantity` - Financial metrics
- `Region`, `State`, `City` - Geographic distribution
- `Segment` - Customer segmentation (Consumer, Corporate, Home Office)

---

## 🔍 Key Questions Answered

| # | Question |
|---|----------|
| 1 | Which product category generates the highest profit? |
| 2 | Which region is the least profitable? |
| 3 | What is the relationship between sales and profit? |
| 4 | When do sales peak and dip throughout the year? |
| 5 | Which sub-categories are losing money? |
| 6 | Who are the top 5 customers by sales? |
| 7 | How do different customer segments perform? |

---

## 📈 Key Findings

### Most Profitable Category
> **Technology** leads with **$145,386** in profit, while **Furniture** underperforms at only **$18,380** despite similar sales volume.

### Least Performing Region
> **Central** region is the weakest at **$39,706**, followed by **South** at **$46,549**. West ($108K) and East ($91K) drive nearly 75% of total profit.

### Problematic Sub-Categories
| Sub-Category | Profit | Status |
|--------------|--------|--------|
| Tables | -$17,725 | ❌ Loses money |
| Bookcases | -$3,472 | ❌ Loses money |
| Supplies | -$1,189 | ❌ Loses money |

### Top 5 Customers by Sales
| Customer | Sales |
|----------|-------|
| Sean Miller | $25,043 |
| Tamara Chand | $19,052 |
| Raymond Buch | $15,117 |
| Tom Ashbrook | $14,596 |
| Adrian Barton | $14,474 |

### Customer Segment Distribution
| Segment | Percentage |
|---------|------------|
| Consumer | 52% |
| Corporate | 30% |
| Home Office | 18% |

### Sales Trends Over Time
| Period | Performance |
|--------|-------------|
| November - December | Peak sales (holiday season) |
| January - February | Lowest sales (post-holiday drop) |
| March - October |  Moderate & stable |
| Year over Year | Consistent growth (2014-2017) |

---

## 📊 Visualizations Created

| Chart | Purpose |
|-------|---------|
|  Line Chart | Sales trend over time (seasonal patterns) |
|  Bar Chart | Sales by category |
|  Bar Chart | Profit by region |
|  Pie Chart | Customer segment distribution |
|  Heatmap | Missing values validation |

---

## 🛠️ Technologies Used

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

| Library | Purpose |
|---------|---------|
| Pandas | Data manipulation & analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive development |

## 📁 Project Structure

Superstore-Sales-Analysis/
│
├── Superstore_Sales_Analysis.ipynb   # Main Jupyter notebook
├── README.md                          # Project documentation


### Notebook Sections

1. Load & Explore Data
2. Data Cleaning
3. Feature Engineering
4. Group By & Aggregation
5. Pivot Tables
6. Data Splitting & Merging
7. Data Visualization
8. Business Insights & Conclusion

## 🚀 How to Run This Project

### Step 1: Clone the Repository
git clone https://github.com/bettycdaba/Superstore-Sales-Analysis.git
cd Superstore-Sales-Analysis

### Step 2: Install Dependencies
pip install -r requirements.txt

### Step 3: Download Dataset
- Download from Kaggle (vivek468/superstore-dataset-final)
- Place Sample - Superstore.csv in the project folder

### Step 4: Run the Notebook
- Open Superstore_Sales_Analysis.ipynb in Jupyter Notebook or Google Colab
- Run all cells sequentially

### Alternative: Open Directly in Colab
https://colab.research.google.com/github/bettycdaba/Superstore-Sales-Analysis/blob/main/Superstore_Sales_Analysis.ipynb

## 💡 Business Recommendations

| Issue | Recommendation |
|-------|----------------|
| Furniture low profit | Review discounts, shipping costs, or pricing strategy |
| Tables losing money | Increase price, reduce costs, or discontinue |
| Central region weak | Investigate local competition, customer behavior |
| Jan-Feb sales drop | Run post-holiday promotions or clearance sales |
| Corporate segment underdeveloped | Increase B2B marketing and volume discounts |

## 📌 Conclusion

The Superstore has balanced revenue across categories and steady year-over-year growth. However, profitability is uneven. Technology drives profit at 145K dollars, while Furniture generates only 18K dollars despite similar sales volume. Tables and Bookcases actually lose money. Regionally, West and East account for 75 percent of profit, while Central and South lag. Sales peak in November and December and drop in January and February. The key lesson is to focus on profitable growth, not just revenue growth.




