# OTT Streaming Analytics: Revenue & Engagement Insights in Excel

## 📖 Project Overview
This project analyzes OTT platform data using Excel to uncover key insights on revenue trends, customer engagement, and high-value audience segments. The analysis is supported by a dynamic dashboard for better business decision-making.

## 🛠️ Tools & Skills
- Microsoft Excel (Excel Functions, Dashboard)
- Data Analysis & Visualization
- Business Insights Generation

##🔎 How I Performed the Analysis

1. Metric Summary (2020–2024)

Since the dataset does not contain 2024 values, I carried forward 2023 data to maintain continuity.

a) Customer at Start → Taken as the “Customer at End” from the previous year.
b) New Customers → Added based on the “new users” column from each respective year.
c) Churned Customers → Taken from the “churned users” column for each respective year.
d) Customer at End → Calculated as:

Customer at Start + New Customers – Churned Customers
Customer at Start + New Customers – Churned Customers
e) Recurring Revenue at Start → Value carried forward from the previous year’s “Recurring Revenue at End.”
f) Net Recurring Revenue → Profit (gains from customers) minus losses (from churned customers).
g) Recurring Revenue at End →
- Considered only active users (users with no churn record).
- For revenue at start and end, took values from these active users.
- Used overlap of active users from both current and previous years to ensure continuity.

2. Additional Insights

a) % of New Users Consuming >1 Language
- Merged Bookings and Content sheets.
- Filtered data for 2023.
- Counted new users watching content in more than one language and calculated percentage.

b) Sci-Fi Tamil Videos Watched by ≥10 Users
- Combined Viewership and Content sheets.
- Filtered for 2022.
- Identified all Sci-Fi Tamil content and checked how many unique users watched each.
- Selected only those with ≥10 viewers.

c) % of Users per Region Engaging with >3% of Ads
- Since 2021 data was unavailable, used 2022.
- Combined Viewership and Bookings sheets.
- Calculated ad engagement for each user.
- Found percentage of users in each region whose ad engagement >3%.

3. Top 10 Most Marketable Tags
Combined Viewership and Content sheets, filtered by 2024 to find the relevant tags and then calculate the required value.

##💡 Insights I Uncovered
Key Insights Uncovered from the Jetflix Data

📉 Churn rate reduced over time → Customers are staying longer on the platform.

💰 Recurring revenue increased exponentially → Indicates stronger retention and better monetization.

🌍 Multi-language viewership trend → New users (from specific years) watch content in more than one language.

Business impact: Suggests opportunity to serve multi-language ads and expand content localization.

🎬 Popular genres identified → Shows which content categories attract the most users.

Business impact: Guides content acquisition & marketing strategy to invest in genres that boost engagement.

📊 Regional ad engagement analysis → Found regions where a higher % of users watch ads beyond 5 seconds.

Business impact: Helps in targeting ad campaigns for better ROI.

🏷️ Top 10 content tags discovered → Certain themes/tags drive significantly higher user engagement.

Business impact: Useful for content recommendation systems and personalized promotions.

