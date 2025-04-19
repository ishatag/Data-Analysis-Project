# Data-Analysis-Project
Cleaned and enhanced a sales dataset using Python (Pandas, NumPy, Matplotlib, seaborn, openpyxl ), adding calculated fields like profit margin and revenue per age. Built an interactive Power BI dashboard to visualize customer trends, product performance, and regional sales insights using KPIs, charts, and slicers to support strategic business decisions.

**Python (Colab) – Data Preparation & Exploration**
The dataset was processed and enriched using Python, focusing on:

Data Exploration: Reviewed structure and summary stats of the dataset (e.g., customer age, unit cost, revenue).

Numerical Analysis: Analyzed Unit_Cost distribution, identifying skewness and outliers.

Categorical Insights: Visualized sales across Age_Group using pie and bar charts.

Correlation Analysis: Built heatmaps and scatter plots to uncover relationships between Revenue, Profit, Customer_Age, and more.

Feature Engineering:

Revenue_per_Age: Revenue efficiency by customer age

Calculated_Cost: Order Quantity × Unit Cost

Calculated_Revenue: Cost + Profit

Adjustments:

Applied a 3% tax increase to unit prices

Increased France’s revenue by 10% for regional impact simulation

Export: Saved the modified dataset (.csv & .xlsx) for use in Power BI


**Power BI – Interactive Dashboard Analysis****

Link: https://app.powerbi.com/reportEmbed?reportId=5ec07e0b-db87-45f7-9817-d32e193a2d3e&autoAuth=true&ctid=76ae1115-1efc-4af2-a536-e2b2443af1a0

Using the modified dataset, an interactive Power BI dashboard was created to highlight the following:

🔹 Customer Insights
Revenue breakdown by Age_Group and Gender

KPI Cards: Total Revenue, Profit, Average Order Quantity

Identified adults (35–64) as the highest-contributing customer segment

🔹 Product Insights
Bar charts showing top-performing and underperforming product sub-categories

Scatter plot: Unit_Cost vs Profit to flag inefficient products

Calculated margins and profitability by category

🔹 Regional & Market Insights
Revenue and profit distribution by Country and State

Slicers for filtering by Age_Group, Country, Product, and Year

Highlighted growth opportunities in specific regions like France

**Outcome & Business Value**
This project offers a practical example of how Python and Power BI can work together to turn raw data into actionable insights. From cleaning and transforming the dataset to building an intuitive dashboard, it supports:

Better customer segmentation

Smarter product pricing and inventory decisions

Targeted regional marketing strategies
