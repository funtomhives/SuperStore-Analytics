# SuperStore-Analytics
An end-to-end exploratory data analysis of the Superstore retail dataset, moving beyond basic visualizations to uncover operational profit leaks, discount thresholds, and regional performance trends using Python.

## Executive Summary & Analysis Breakdown

| Analysis Module | Business Question | Technique / Tool | Key Strategic Insight |
| :--- | :--- | :--- | :--- |
| **Profit Leaders** | Which product sub-categories drive the bottom line? | Pandas Aggregation, Bar Chart | Copiers and Phones are massive profit drivers, while certain office supplies lag behind. |
| **Loss Concentration** | Where is the business bleeding capital? | Categorical Filtering, Pie Chart | **Tables** and Bookcases account for heavy net losses despite steady sales volume. |
| **Discount Optimization** | What is the optimal discount rate before it hurts? | Conditional Color-Coding, Bar Chart | Identified the **20% Sweet Spot**; discounts exceeding 30% cause severe profit leakage. |
| **Regional Performance** | How do geographical regions stack up in Sales vs. Profit? | Scatter Plot (Quadrant Analysis) | **West & East** dominate the top-right quadrant, while Central and South face margin compression. |
| **Time Trends & Seasonality** | How do revenue and profit scale over multi-year timelines? | Dual-Axis Line Graph (`matplotlib`), Resampling | Proved a steady upward scaling of revenue and profit from 2023 to 2026 without hidden margin crashes. |

---

## Tech Stack & Libraries
* **Language:** Python 
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib (Custom Legends, Dual-Axis, Scatter Quadrants)
* **Environment:** Jupyter Notebook


## 🚀 How to Run Locally
```  git clone [https://github.com/funtomhives/superstore-profit-analytics.git](https://github.com/YOUR-USERNAME/superstore-profit-analytics.git) ```
