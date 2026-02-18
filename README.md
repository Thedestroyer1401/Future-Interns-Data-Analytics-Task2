
📌 Task Overview
This project was developed for my internship to address the challenge of customer churn in the telecommunications industry. Using the Telco Customer Churn dataset, I built an interactive Power BI dashboard to identify high-risk customer segments and provide data-driven strategies to increase retention.

📊 Business Metrics Summary
The following were established to track business health:

Total Customers: 7,043

Overall Churn Rate: 26.54%

Total Revenue Lost: $2.86M

🔍 Key Findings & Visual Analysis
Through data modeling and visualization, three primary drivers of churn were identified:

1. Contractual Risk
Customers on Month-to-month contracts are the primary source of churn (42.7%). Long-term contracts (1 and 2 years) show significantly higher loyalty, suggesting that contract structure is the strongest predictor of retention.

2. The First 6 Months "Danger Zone"
Analysis of customer tenure revealed that 52% of new customers leave within the first 6 months. This indicates a critical need for improved onboarding and early-stage engagement.

3. Service & Technology Impact
Fiber Optic users churn at more than double the rate of DSL users. Additionally, customers who do not utilize Tech Support or Online Security services are much more likely to cancel their subscriptions.

🛠️ Technical Implementation
Data Cleaning: Used Power Query to handle missing values in TotalCharges and standardized data types for mathematical analysis.

Feature Engineering: Created a custom Tenure Group column to categorize the customer lifecycle.

DAX Measures: Developed complex measures for Churn Rate, Churned Count, and Revenue Impact.

Advanced Visuals: Utilized Donut Charts, Stacked Column Charts, and Treemaps to provide a multi-dimensional view of the data.

💡 Strategic Recommendations
Contract Migration: Incentivize Month-to-month users to switch to annual plans through targeted discounts.

Enhanced Onboarding: Launch a "New Customer Success" program specifically for the 0-6 month cohort.

Service Audit: Conduct a technical review of Fiber Optic infrastructure to address potential quality issues.

Value-Added Services: Promote Tech Support and Security features as "Retention Tools" to increase customer "stickiness."

📂 Repository Contents
WA_Fn-UseC_-Telco-Customer-Churn.csv: The raw dataset.

task 2.pbix: The complete Power BI dashboard file.

task 2.pdf: A high-resolution image of the final report.

👤 Author
Aman Sayyad
BBA(CA) Student
