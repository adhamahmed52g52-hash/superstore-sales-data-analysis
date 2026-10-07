\# 📊 Advanced Superstore Sales Analysis \& Business Insights



An end-to-end exploratory data analysis (EDA) and automated reporting project built with Python. This project evaluates multi-year retail transactions from the Superstore dataset to uncover profitability drivers, sales trends, discount impacts, and operational returns.



\---



\## 🚀 Key Project Objectives

\- Inspect and clean raw, multi-sheet retail data.

\- Engineer business-critical features (Profit Margins, Shipping Times, Sales Tiers).

\- Analyze KPIs across product categories, geographic regions, and customer segments.

\- Detect outliers and evaluate the profitability threshold of applied discount strategies.

\- Visualize performance through customized analytical dashboards.



\---



\## 🛠️ Tech Stack \& Libraries

\- \*\*Language:\*\* Python

\- \*\*Data Manipulation \& Analysis:\*\* Pandas, NumPy

\- \*\*Data Visualization:\*\* Matplotlib, Seaborn

\- \*\*Environment:\*\* Jupyter Notebook / Python Scripts



\---



\## 📈 High-Level KPIs \& Metrics

\- \*\*Total Sales:\*\* $2.30M ($2,297,200.86)

\- \*\*Total Profit:\*\* $286.40K ($286,397.02)

\- \*\*Total Quantity Sold:\*\* 37,873 units

\- \*\*Total Orders:\*\* 5,009

\- \*\*Overall Profit Margin:\*\* 12.47%

\- \*\*Average Order Value (AOV):\*\* $458.61

\- \*\*Overall Return Rate:\*\* \~8.00% (800 orders)



\---



\## 💡 Core Business Insights

1\. \*\*Category Dynamics:\*\* Technology delivered the highest revenue and net profit, whereas Furniture exhibited significantly depressed profit margins.

2\. \*\*Geographical Performance:\*\* The West region produced both maximum sales volume and the highest profit margin; the Central region yielded the lowest margins.

3\. \*\*Discount Thresholds:\*\* Discounts above 20% consistently triggered operational net losses, with discounts exceeding 50% yielding severe negative margins (-119.2%).

4\. \*\*Growth Trajectory:\*\* Enterprise sales and profit metrics maintained a continuous upward trend from 2016 through 2019.



\---



\## ⚙️ Workflow \& Methodology

1\. \*\*Data Loading \& Inspection:\*\* Loaded transaction records, managers, and return logs; checked shape, nulls, and duplicate values.

2\. \*\*Cleaning \& Preprocessing:\*\* Handled missing postal codes and standardized order/shipping timestamps into `datetime`.

3\. \*\*Feature Engineering:\*\* Derived `Profit Margin (%)`, `Shipping Duration (days)`, and binned `Sales Performance` tiers using `pd.cut()`.

4\. \*\*Statistical \& Outlier Auditing:\*\* Applied Interquartile Range (IQR) filtering, isolating 1,167 extreme sales outliers.

5\. \*\*Dashboard Visualizations:\*\* Structured 11 focused analytical plots and 4 modular executive dashboards.



\---



\## 👤 Author

\- \*\*Adham Ahmed\*\*

