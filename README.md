# ecommerce-analytics-customer-retention
End-to-end ecommerce analytics project using Excel, SQL Server, Python machine learning, and Power BI.

Project Overview
This project is an end-to-end ecommerce analytics case study built to understand sales performance, customer behaviour, delivery performance, and customer churn risk.
The aim was to take raw ecommerce data and turn it into useful business insights using Excel, SQL Server, Python, and Power BI.
The project answers practical business questions such as:
Which region is generating the most revenue?
Which product category performs best?
How does delivery performance affect customer satisfaction?
Which customers are more likely to stop purchasing?
What can the business do to improve retention?
Tools Used
Microsoft Excel
SQL Server Management Studio (SSMS)
Python
Jupyter Notebook
Power BI
GitHub
Dataset
The dataset contains around 5,000 ecommerce transaction records.
Main fields used:
order_id
order_date
customer_id
product_category
region
quantity
unit_price
discount
payment_method
delivery_days
customer_rating
revenue
Project Workflow
1. Excel Data Cleaning
Excel was used to clean and prepare the raw dataset before analysis.
Cleaning steps included:
removed duplicate rows
fixed date formats
standardised region names
cleaned payment method values
checked missing values
validated revenue calculations
prepared the file for SQL import
This step was important because clean data gives more reliable analysis and dashboard results.
2. SQL Server Analysis
The cleaned data was imported into SQL Server.
SQL was used to:
store the cleaned dataset
run business queries
calculate revenue by region and product
analyse customer ratings and delivery performance
create SQL views for Power BI
practise joins, aggregations, window functions, CTEs, and rolling averages
This helped create a stronger reporting layer before building the dashboard.
3. Power BI Dashboard
Power BI was used to create interactive dashboards for business users.
The dashboard includes:
total revenue
total orders
revenue by region
revenue by product category
monthly revenue trend
rolling average sales trend
average customer rating
delivery performance
customer churn risk
feature importance from the churn model
Slicers were added so users can filter results by region, product category, and payment method.
4. Python and Machine Learning
Python and Jupyter Notebook were used for advanced analytics.
The Python work included:
customer segmentation
revenue prediction
churn prediction
ROC/AUC model evaluation
feature importance analysis
A churn prediction model was built to identify customers who may stop purchasing. This gives the business a way to target high-risk customers before they leave.
Key Business Insights
1. West region performed best
The West region generated the highest total revenue. This suggests stronger customer demand and better sales activity in that region.
2. Electronics was the strongest product category
Electronics produced the highest sales contribution. This category is important because it has stronger revenue potential and likely higher order value.
3. Delivery performance affected customer experience
Longer delivery times were linked with weaker customer ratings. This shows that delivery speed and reliability are important for customer satisfaction.
4. Repeat customers were more valuable
Customers with more orders were more likely to be high-value customers. This means customer retention and repeat purchasing are key business priorities.
5. Churn risk was linked to customer experience
Customers with lower ratings and weaker engagement were more likely to become high churn-risk customers.
6. Discounts alone were not enough
Discounts had less impact on customer retention compared with order frequency, customer ratings, and delivery performance.
Business Recommendations
Based on the analysis, the business should:
focus marketing efforts on high-performing regions such as West
prioritise Electronics inventory and campaigns
improve delivery performance to protect customer satisfaction
build loyalty programs for repeat customers
target high-risk customers with retention campaigns
monitor churn risk regularly using Power BI dashboards
Dashboard Preview
Add your dashboard screenshots here:
![Executive Dashboard](images/executive_dashboard.png)

![Churn Dashboard](images/churn_dashboard.png)

![Revenue Dashboard](images/revenue_dashboard.png)

Business Impact
This project shows how data can help an ecommerce business:
understand where revenue comes from
improve customer retention
identify high-value customers
reduce churn risk
improve delivery operations
support better marketing decisions
turn raw data into clear business insights
Skills Demonstrated
Excel
Data cleaning
Duplicate removal
Date formatting
Data validation
SQL
SELECT, WHERE, GROUP BY, HAVING
Joins
CTEs
Window functions
Rolling averages
SQL views
Power BI
KPI cards
Interactive dashboards
Slicers
Matrix visuals
Trend charts
Churn risk dashboard
Python
Pandas
Customer segmentation
Random Forest modelling
Churn prediction
ROC/AUC evaluation
Feature importance analysis
Project Files
ecommerce-analytics-customer-retention/
│
├── README.md
├── business_insights.md
├── project_structure.md
├── powerbi/
│   └── Ecommerce_Dashboard.pbix
├── reports/
│   └── Ecommerce Analytics Case Study Portfolio Paper.docx
└── images/
    ├── executive_dashboard.png
    ├── churn_dashboard.png
    └── revenue_dashboard.png
Final Summary
This project demonstrates a complete analytics workflow from data cleaning to business reporting and predictive modelling.
It combines Excel, SQL, Python, and Power BI to solve a realistic ecommerce business problem and provide clear recommendations for improving sales, customer experience, and retention.
