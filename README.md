# Zomato-Sales-Analysis
This project analyzes Zomato's business performance through Sales Analysis, focusing on revenue trends, top-performing restaurants, and customer insights. The analysis was conducted using datasets containing restaurant, user, and order information.

Key Objectives:

Analyze sales dynamics over time.
Identify top-performing restaurants.
Understand sales distribution across cities.
Evaluate customer purchasing behavior.
Assess day-wise sales trends to validate hypotheses.
Data Sources

The following CSV files were used:

orders.csv: Order details including order IDs and sales amount.
restaurant.csv: Information about restaurants (names, locations).
users.csv: Customer details.
menu.csv and food.csv: Menu items and food details.
Data Cleaning and Preparation
Data was cleaned and prepared using Excel and joined in Tableau as follows:

Orders were linked to Restaurants via restaurant_id.
Orders were linked to Users via user_id.
Irrelevant and duplicate records were removed.
Missing values were handled, and data formats were standardized.
Visualizations and Insights

Visual/Example: 

![Sales Distribution Across Cities](https://github.com/PaulC1337/Zomato-Sales-Analysis/blob/main/Sales%20Distribution%20Across%20Cities.png)


Using a few SQL queries I was able to form tables, the link to those queries can be found below

https://docs.google.com/document/d/1TPTK_kzrs0nt56bEXOMR1sG_tTj1vKtKPWzfVrgassI/edit?usp=sharing

The following visualizations were created in Tableau to meet project objectives:

Sales Dynamics Over Time

Visualization: Line Chart
Insight: Sales peaked in early 2018 but declined post-2019, with notable spikes likely tied to promotions or festive seasons.
Top Restaurants by Revenue

Visualization: Bar Chart
Insight: Domino's Pizza emerged as the top revenue generator, followed by Kouzina Kafe and Sweet Truth.
Sales Distribution Across Cities

Visualization: Map/Bar Chart
Insight: Major cities dominate sales, with growth opportunities in underperforming regions.
Customer Insights: Sales by User

Visualization: Scatter Plot
Insight: A small group of high-value customers drives significant revenue.
Sales Heatmap by Day of the Week

Visualization: Heatmap
Insight: Sales are highest on Fridays, disproving the hypothesis of weekend peaks.
Key Performance Indicators (KPIs)
Total Sales: ₹964,259,275
Total Orders: 566
Average Order Value (AOV): ₹122,446
Final Dashboard

The interactive Tableau dashboard can be accessed here: https://public.tableau.com/app/profile/paul.john.cannarella.jr/viz/ZomatoSales-Analysis/DashboardAnalysis#1

Summary of Findings

Sales Trends: Peak sales occurred in early 2018, with a decline post-2019.
Top Performers: Domino's Pizza and similar brands are major contributors.
Geographic Insights: Sales are concentrated in major cities.
Customer Insights: High-value customers generate disproportionate revenue.
Day-Wise Trends: Fridays see the highest sales.
Recommendations
Launch targeted campaigns on Fridays.
Leverage partnerships with high-revenue restaurants like Domino's Pizza.
Explore growth opportunities in underperforming regions.
Implement strategies to retain high-value customers.

Technologies Used
Data Cleaning: Excel
Data Visualization: Tableau Public
Data Sources: CSV Files

