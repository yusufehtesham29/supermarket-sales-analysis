<div align="center">



\# 🛒 Supermarket Sales Analysis \& Retail Performance Platform

\### Comprehensive Retail Analytics, Category Contribution \& Statistical Dispersion Diagnostics



\[!\[Stack](https://img.shields.io/badge/Tech\_Stack-Python\_%7C\_Pandas\_%7C\_Excel-239120?style=for-the-badge\&logo=python\&logoColor=white)](https://github.com/yusufehtesham29/supermarket-sales-analysis)

\[!\[License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/licenses/MIT)



</div>



\---



\## 📌 Executive Summary



This project delivers an end-to-end retail sales analysis across \*\*8,523 grocery transactions\*\* spanning 16 product categories, 4 outlet types, and 3 store tiers. The workflow covers exploratory data profiling, feature standardization, distribution diagnostics, and category-level benchmarking using \*\*Python (Pandas, NumPy, Matplotlib, Seaborn)\*\* and \*\*Microsoft Excel\*\*.



| Total Sales Revenue | Average Ticket Value | Avg Product Visibility | Total Records | Outlier Count (IQR) | Correlation (Visibility vs. Sales) |

| :---: | :---: | :---: | :---: | :---: | :---: |

| \*\*$1,201,681.49\*\* | \*\*$140.99\*\* | \*\*6.61%\*\* | \*\*8,523\*\* | \*\*0\*\* | \*\*-0.0013\*\* |



\---



\## 💡 Key Business Findings by Objective



\### Objective 1: Overall Sales Performance

\* \*\*Total Revenue:\*\* Gross sales reached \*\*$1,201,681.49\*\* across all 8,523 recorded transactions.

\* \*\*Average Sales Value:\*\* Baseline average spend per product record sits at \*\*$140.99\*\*.

\* \*\*Shelf Visibility Allocation:\*\* Average product shelf allocation stands at \*\*6.61%\*\* (0.0661).



\### Objective 2: Product Category \& Outlet Sales Comparison

\* \*\*Top 4 Concentration:\*\* The top 4 categories generate \*\*50.60%\*\* ($608,093.41) of total revenue, while the remaining 12 categories contribute \*\*49.40%\*\* ($593,588.08).

&#x20; \* \*Fruits and Vegetables:\* $178,124.08 (14.82%)

&#x20; \* \*Snack Foods:\* $175,433.92 (14.60%)

&#x20; \* \*Household:\* $135,976.53 (11.32%)

&#x20; \* \*Frozen Foods:\* $118,558.88 (9.87%)

\* \*\*Top vs. Bottom Category:\*\* \*\*Fruits and Vegetables\*\* leads overall turnover, while \*\*Seafood\*\* accounts for the lowest revenue ($9,077.87; 0.76% of sales).

\* \*\*Outlet Footprint:\*\* \*\*Supermarket Type1\*\* is the primary volume driver, generating \*\*65.54%\*\* ($787,549.89) of all sales across 5,577 records.



\### Objective 3: Outlet Performance \& Shelf Relationships

\* \*\*Fat Content Split:\*\* \*\*Low Fat\*\* products drive \*\*64.60%\*\* ($776,319.69) of revenue across 5,517 records, compared to \*\*35.40%\*\* ($425,361.80) for \*\*Regular\*\* items across 3,006 records.

\* \*\*Product Visibility vs. Sales:\*\* Pearson correlation between product visibility and revenue is \*\*-0.0013\*\*. Allocating more physical shelf display ratio does not drive higher sales, indicating potential over-allocation of display space to low-velocity inventory.



\### Objective 4: Statistical Analysis of Sales

\* \*\*Central Tendency:\*\* Mean sales ($140.99) aligns closely with the median sales ($143.01), showing a balanced distribution.

\* \*\*Dispersion Metrics:\*\* Standard deviation of \*\*$62.28\*\* and an Interquartile Range (IQR) of \*\*$91.82\*\* (Q1: $93.83, Q3: $185.64).

\* \*\*Outlier Detection:\*\* Applying Tukey's $1.5 \\times \\text{IQR}$ fence reveals \*\*0 outliers\*\* (lower fence: -$43.90, upper fence: $323.37). Sales range from a minimum of \*\*$31.29\*\* to a maximum of \*\*$266.89\*\*.

\* \*\*Tier Homogeneity:\*\* Average transaction values remain uniform across location tiers (Tier 1: $140.87, Tier 2: $141.17, Tier 3: $140.94) and outlet formats (\~$140–$141).



\---



\## 🛠 Repository Structure



```text

supermarket-sales-analysis/

├── Supermarket Sales Analysis Dashboard.xlsx   # Original dataset

├── cleaned\_supermarket\_sales.csv               # Standardized output dataset

├── analysis.ipynb                              # Python analysis \& data pipeline notebook

├── .gitignore

└── README.md

