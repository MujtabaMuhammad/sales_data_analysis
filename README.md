# SalesDataAnalysis
________________________________________
Sales Data Analysis Project
This project focuses on understanding sales patterns across three different branches of a retail store using Matplotlib and Seaborn for data visualization. The dataset, sourced from Kaggle, provides detailed information about sales transactions, including customer attributes, product details, and revenue metrics.
Context
This study aims to identify the best-selling products and analyze trends in gross income over a three-month period. The insights gained can assist in making data-driven decisions about product offerings, store layout, and inventory management. For example:
•	Identifying underperforming products for potential discontinuation.
•	Rearranging product placements to optimize sales.
•	Improving seasonal forecasting for better inventory management.
Note About the Dataset
The dataset includes a unique feature where the tax rate for all products is exactly equal to the gross income. This was both verified by me and something other analysts on Kaggle had commented on. It did result in somewhat of boring analysis without many outliers in terms of understanding sales 
________________________________________
Content
Each row in the dataset represents a unique customer transaction, and the columns provide various attributes, such as:<br>
•	Branch: The store branch where the transaction occurred. Represented by letter A, B and C. <br>
•	City: The city where the branch is located, A) Yagon, B) Mandalay, C) Naypyitaw <br>
•	Customer Type: Member vs Nonmembers.<br>
•	Gender: Gender of the customer.<br>
•	Product Line: The category of the purchased product, Sports and Travel, Electronic Accessories, Home and Lifestyle,<br> &nbsp; Fashion Accessories, Food and Beverages, Health and Beauty <br>
•	Unit Price: Price per unit of the product.<br>
•	Tax: 5% tax applied to the transaction.<br>
•	Total: Total amount paid, including tax.<br>
•	Date: Date of the transaction.<br>
•	Time: Time of the transaction.<br>
•	Payment: Payment method used, cash, ewallet, credit card, payment.<br>
•	COGS: Cost of goods sold.<br>
•	Gross Margin Percentage: Margin of the sale.<br>
•	Gross Income: Profit from the transaction.<br>
•	Day of the week: While not in the trends, this would have been a very useful thing to include.
________________________________________
Objective
The primary goals of this project are:
1.	Analyze Trends: Understand sales trends and gross income over time.
2.	Identify Best-Selling Products: Determine the most popular product lines across branches.
3.	Seasonality Analysis: Investigate seasonal variations in sales.
4.	Generate Insights: Provide actionable insights to optimize sales and inventory management.
________________________________________
Approach
1. Data Preprocessing
•	Data Cleaning: Handled missing values and ensured consistency in data formatting.
•	Feature Engineering: Encoded categorical variables and calculated derived metrics like monthly and quarterly totals.
•	Scaling: Applied feature scaling where required for analysis and visualizations.
2. Exploratory Data Analysis (EDA)
•	Conducted a detailed investigation of: 
o	Revenue Trends: Monthly and quarterly gross income.
o	Product Line Performance: Best and worst-performing product lines.
o	Branch Comparisons: Performance of different branches over the analysis period.
o	Seasonality: Trends and patterns indicating seasonality in sales.
•	Tools: Used Matplotlib for line charts and Seaborn for enhanced visualizations like heatmaps and bar plots.
3. Insights
•	Analyzed customer demographics (gender, customer type) for sales patterns.
•	Explored correlations between product lines and payment methods.
•	Evaluated branch-wise performance for regional decision-making.
4. Optional Additions
•	Modeling (Future Scope): While this project focuses on descriptive analysis, future iterations may involve predictive modeling for sales forecasting using TensorFlow.
•	Interactive Dashboard: Building a dashboard with Streamlit or Plotly for a dynamic, user-friendly interface.
________________________________________
Dependencies
•	Python 3
•	Libraries: <br>
o	pandas: For data manipulation. <br>
o	numpy: For numerical computations.<br>
o	matplotlib: For basic visualizations.<br>
o	seaborn: For advanced and aesthetic visualizations. <br>
o	tensorflow (optional): For potential predictive modeling. <br>
________________________________________
Summary Report
The visualizations and findings from this project are designed to be actionable and insightful for retail decision-making. Example visualizations include:
•	Line Chart: Trends in gross income over three months.
•	Bar Chart: Sales comparison of product lines across branches.
•	Heatmap: Correlation between revenue metrics and other factors like customer type or branch.
By integrating data-driven insights, the project highlights opportunities for improving sales strategies and operational efficiency.
________________________________________

