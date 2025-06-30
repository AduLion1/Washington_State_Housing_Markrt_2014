Washington Housing Market Analysis (May–July 2014)
This project presents a detailed analysis of housing prices in Washington State for the months of May, June, and July 2014, using a dataset sourced from Kaggle. The goal was to uncover trends and insights in real estate sales across various cities, using data-driven techniques to support decision-making and visualization.
📂 Dataset: USA House Prices – Kaggle
📁 GitHub Repository: Washington State Housing Market 2014

 Tools & Technologies Used:
•	SQL Server: For data cleaning, transformation, and complex queries
•	Common Table Expressions (CTE): Used to structure and combine multiple SQL queries
•	Power BI: For building interactive dashboards and presenting data visually
•	Data Modeling: Created calculated columns such as House_Age and Price_Per_Bedroom
 Data Preparation & Cleaning:
•	Imported and cleaned the dataset in SQL Server.
•	Extracted month and year from the raw date field for time-based analysis.
•	Computed house age using 2025 - year_built to analyze depreciation trends.
•	Calculated price per bedroom, avoiding division by zero using NULLIF(bedrooms, 0).
•	Used GROUP BY and CTEs to create summarized data views by city and month.
Power BI Dashboard Highlights:
•	Total sales volume by city
•	Sales trends per month (May–July)
•	Price per bedroom by location
•	Interactive map of city-level prices
•	Key indicators: total sales, average price, one-bedroom price totals

Key Insights:
•	Seattle Dominates: Nearly $1 billion in total sales—over 40% of the market.
•	June Peaks: 52.1% of total sales occurred in June, the highest month.
•	Strong 1-Bedroom Market: $686M in sales, showing high demand for smaller homes.
•	Statewide Average Price: $224.26K, reflecting competitive housing costs.
•	Bellevue & Redmond: High value per bedroom; Bellevue alone totaled $59.7M.
Project Impact:
This project strengthened my ability to use SQL for real-world data wrangling, develop reusable query structures with CTEs, and communicate findings through Power BI dashboards. It demonstrates my skills in transforming raw data into actionable insights and building analytical products that tell a clear story.

