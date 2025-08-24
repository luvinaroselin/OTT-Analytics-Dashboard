# OTT Streaming Analytics: Revenue & Engagement Insights in Excel  

## 📖 Project Overview  
This project analyzes OTT platform data using Excel to uncover key insights on revenue trends, customer engagement, and high-value audience segments. The analysis is supported by a dynamic dashboard for better business decision-making.  

### 🛠️ Tools & Skills  
- Microsoft Excel (Functions: VLOOKUP, INDEX & MATCH, SUMPRODUCT, COUNTA, FREQUENCY, FILTER)  
- Pivot Tables for summarization  
- Data Analysis & Business Insights  

---

## 🔎 How I Performed the Analysis  

### 1. Metric Summary (2020–2024)  
Since the dataset does not contain 2024 values, I carried forward 2023 data to maintain continuity.  

- **Customer at Start** → Taken as the “Customer at End” from the previous year.  
- **New Customers** → Added based on the “new users” column from each respective year.  
- **Churned Customers** → Taken from the “churned users” column for each respective year.  
- **Customer at End** →  
  `Customer at Start + New Customers – Churned Customers`  
- **Recurring Revenue at Start** → Value carried forward from the previous year’s “Recurring Revenue at End.”  
- **Net Recurring Revenue** → Profit (gains from customers) minus losses (from churned customers).  
- **Recurring Revenue at End** →  
   - Considered only active users (users with no churn record).  
   - For revenue at start and end, took values from these active users.  
   - Used overlap of active users from both current and previous years to ensure continuity.  

---

### 2. Additional Insights  

- **% of New Users Consuming >1 Language**  
   - Merged *Bookings* and *Content* sheets.  
   - Filtered data for 2023.  
   - Counted new users watching content in more than one language and calculated percentage.  

- **Sci-Fi Tamil Videos Watched by ≥10 Users**  
   - Combined *Viewership* and *Content* sheets.  
   - Filtered for 2022.  
   - Identified all Sci-Fi Tamil content and checked unique viewers.  
   - Selected only videos with ≥10 viewers.  

- **% of Users per Region Engaging with >3% of Ads**  
   - Used 2022 data (2021 not available).  
   - Combined *Viewership* and *Bookings* sheets.  
   - Calculated ad engagement for each user.  
   - Found % of users in each region whose ad engagement exceeded 3%.  

---

### 3. Top 10 Most Marketable Tags  
- Combined *Viewership* and *Content* sheets.  
- Filtered for 2024.  
- Counted tags based on user interactions and popularity.  
- Ranked tags and selected the top 10 most marketable ones.  

---

## 💡 Insights I Uncovered  

- **Churn rate reduced over time** → Customers are staying longer on the platform.  
- **Recurring revenue increased exponentially** → Indicates stronger retention and better monetization.  
- **Multi-language viewership trend** → New users from certain years consume content in more than one language.  
  - *Business impact*: Opportunity to serve multi-language ads and expand content localization.  
- **Popular genres identified** → Certain content categories attract the highest number of viewers.  
  - *Business impact*: Guides content acquisition & marketing strategy to focus on genres that boost engagement.  
- **Regional ad engagement analysis** → Found regions where a higher % of users watch ads beyond 5 seconds.  
  - *Business impact*: Helps optimize ad targeting for better ROI.  
- **Top 10 content tags discovered** → Some themes/tags drive significantly higher engagement.  
  - *Business impact*: Useful for recommendation systems and personalized promotions.
