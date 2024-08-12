# Customer Segmentation Using RFM Analysis
This project uncovers customer behavior patterns of a UK retail company through segmentation analysis using the RFM (Recency, Frequency, Monetary) model. The objective is to identify distinct customer segments and develop targeted marketing strategies to improve customer engagement, enhance revenue stability, and optimize marketing expenditures.
## Background
The retail company faced significant fluctuations in sales, with 50% of total sales concentrated in the last 4 months of the year. To address this instability, the company aimed to understand consumer behavior better. By analyzing transactional data, customer segments were identified to develop more effective marketing strategies.
## Business Objective
- Identify high-value customers and develop appropriate marketing strategies to target them.
- Improve the effectiveness of marketing promotions to support revenue generation.
- Achieve revenue stability throughout the year.
## Business Questions
- How can customer segmentation with RFM analysis help the company better understand and target different customer segments?
- How can the company develop unique marketing strategies to increase advertising effectiveness?

## Methodology
### RFM Analysis
RFM analysis categorizes customers based on:
- Recency: Days since the last purchase.
- Frequency: Total number of transactions.
- Monetary: Total amount spent.
### K-Means Clustering
![download (7)](https://github.com/user-attachments/assets/b9d98c38-c411-4873-ad08-f649f1f225e9)
K-Means clustering was applied to group customers based on their RFM profiles. The optimal number of clusters (K = 3) was determined using the Elbow method.

## Results
### Exploratory Data Analysis
- Sales Fluctuations: Significant revenue peaks in November due to seasonal factors like Black Friday and Cyber Monday.
- Discount Strategy: The effectiveness of promotions was questioned as the high discount allocation did not proportionately increase revenue.
- Customer Retention: Notable customer retention in December 2010, indicating successful onboarding during that period.
### Customer Segmentation
![download (9)](https://github.com/user-attachments/assets/ba5a2b73-29b8-407d-81f5-75738b64017e)
- Cluster 0 (Best Customer): Low recency, high frequency, very high monetary value.
- Cluster 1 (At Risk Customer): High recency, low frequency, low monetary value.
- Cluster 2 (Regular Customer): Low recency, medium frequency, medium monetary value.

## Recommendations
### Best Customer
- Objective: Maintain loyalty and increase lifetime value.
- Strategies: VIP programs, referral incentives, early access to new products, deeper personalization.
### Regular Customer
- Objective: Increase purchase frequency and transaction value.
- Strategies: Upselling, frequent buyer discounts, product recommendations, bundle offers.
### At Risk Customer
- Objective: Reactivate purchases and increase engagement.
- Strategies: Win-back campaigns, limited edition products, satisfaction surveys, personalized emails.

## Conclusion
This analysis provides a foundation for understanding customer behavior and designing targeted marketing strategies. By focusing on high-value and regular customers while implementing retention strategies for at-risk customers, the company can improve revenue stability and optimize promotional spending.

For a detailed analysis and insights, please check out the full report on [Medium](https://medium.com/@febbyngrni/customer-segmentation-using-rfm-analysis-in-retail-uk-d7f22a40a20c).
