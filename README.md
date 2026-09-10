# ecommerce-sales-analysis
Superstore Sales & Profitability Analysis
Project Overview

This project analyzes the Superstore retail dataset to understand sales performance, profitability, customer segments, regional performance, product performance and discount-related profitability.

Python was used for data cleaning, exploratory data analysis and visualization, while Power BI was used to create an interactive business dashboard.

Problem Statement

Retail businesses need to understand which products, categories, regions and customer segments contribute most to sales and profit. High sales do not always result in high profitability, so this project analyzes both revenue and profit to identify areas of strong and weak business performance.

Project Objectives
Analyze overall sales and profitability.
Identify high-performing and low-performing product categories.
Compare regional performance.
Analyze customer segment performance.
Identify sales and profit trends over time.
Examine the relationship between discount and profit.
Build an interactive Power BI dashboard.
Provide data-driven business recommendations.
Dataset Description

The project uses the Superstore Dataset Final from Kaggle.

The dataset contains retail transaction information including:

Order details
Customer information
Product information
Categories and sub-categories
Sales
Quantity
Discount
Profit
Region
Segment
Order and shipping dates
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab
Power BI
Git
GitHub
Data Cleaning Process

The dataset was inspected for structure, data types, missing values and duplicate records.

The following preparation steps were performed:

Inspected rows and columns.
Checked data types.
Checked missing values.
Checked duplicate records.
Converted Order Date and Ship Date to datetime format.
Created Year and Month fields.
Created Year-Month for time-series analysis.
Created Shipping Days.
Checked numerical variables for unusual values.
Saved the prepared dataset as superstore_cleaned.csv.
Exploratory Data Analysis

The analysis examined:

Overall sales and profit.
Category performance.
Sub-category performance.
Regional performance.
Customer segment performance.
Yearly sales and profit.
Discount and profit correlation.
Potential outliers.
Top and low-performing products.
Key Performance Indicators
Metric	Result
Total Sales	$2,297,200.86
Total Profit	$286,397.02
Total Orders	5,009
Total Customers	793
Total Quantity	37,873
Profit Margin	12.47%
Visualizations

The project includes the following visualizations:

Sales by Category
Profit by Region
Monthly Sales Trend
Sales vs Profit
Profit by Sub-Category
Correlation Heatmap
Power BI Dashboard

The interactive Power BI dashboard contains:

Total Sales KPI
Total Profit KPI
Total Orders KPI
Profit Margin KPI
Sales by Category
Profit by Region
Monthly Sales Trend
Sales vs Profit
Profit by Sub-Category
Year, Region, Category and Segment slicers
Key Business Insights
1. Technology is the strongest category

Technology generated $836,154.03 in sales and $145,454.95 in profit, making it the strongest overall product category.

2. West is the strongest region

The West region generated $725,457.82 in sales and $108,418.45 in profit, making it the top-performing region by both sales and profit.

3. Copiers are highly profitable

Copiers generated $55,617.82 in profit from $149,528.03 in sales, making them the most profitable sub-category.

4. Tables have negative profitability

Tables generated $206,965.53 in sales but recorded a loss of $17,725.48. This demonstrates that high sales do not necessarily guarantee high profitability.

5. Consumer is the largest customer segment

The Consumer segment generated $1,161,401.34 in sales and $134,119.21 in profit, making it the largest contributor among the customer segments.

6. 2017 had the highest annual sales

Annual sales reached $733,215.26 in 2017, the highest sales value among the years analyzed.

7. Discount and profit have a weak negative relationship

The correlation between discount and profit was -0.219, indicating a weak negative association between discount levels and profit.

Business Recommendations
1. Review pricing and discounts

The company should review pricing and discount strategies for low-profit products, particularly Tables and Bookcases, to improve profitability.

2. Focus on high-performing products and categories

Marketing and sales resources should continue to support strong-performing areas such as Technology, Copiers, Phones and Accessories.

3. Investigate weaker regional performance

The Central region generated the lowest regional profit. Management should investigate its product mix, pricing, discount levels and operating costs.

Project Files
data/
notebooks/
visualizations/
powerbi/
report/
presentation/

Conclusion

The analysis shows that the Superstore generated approximately $2.30 million in sales and $286,397.02 in profit, with an overall profit margin of 12.47%.

Technology, the West region and the Consumer segment were important contributors to overall performance. However, certain sub-categories, particularly Tables and Bookcases, generated losses despite having significant sales.

The combination of Python analysis and Power BI visualization provides a comprehensive view of business performance and supports data-driven decision-making.

