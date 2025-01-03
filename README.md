# Customer-Segmentation-Using-RFM-Analysis

# Project Overview
This analysis was performed on a dataset containing transaction data from 2010 to 2011. The primary objective was to identify distinct customer groups by applying RFM analysis and KMeans clustering to segment customers. These insights allow businesses to craft targeted marketing strategies, optimize customer lifetime value, and foster long-term loyalty.

Key Metrics:
Recency (R): Days since the last purchase.
Frequency (F): Total number of purchases.
Monetary (M): Total value of purchases.

# Methodology
Data Preprocessing:

Removed missing values from critical fields such as CustomerID and Description.
Ensured consistency in data types and handled encoding issues.
RFM Calculation:

Used Python to compute RFM metrics for each customer.
Derived insights about purchasing patterns and created a clean RFM dataset.
RFM Segmentation and Clustering:

Employed the Elbow Method to determine the optimal number of clusters (K = 3).
Used KMeans Clustering to group customers into distinct clusters.
Visualized results through scatterplots.
Segment Profiling:

Analyzed the behavioral characteristics of each customer segment:
Cluster 0: Moderate recency, frequency, and monetary value.
Cluster 1: High recency, low frequency, and low monetary value.
Cluster 2: High frequency, very low recency, and extremely high monetary value.
Marketing Recommendations:

Proposed tailored strategies for each segment, including loyalty programs, re-engagement campaigns, and premium customer retention initiatives.
Additional Insights:

Identified sales trends by day, time, and season.
Highlighted high-value product categories and their profitability.

# Results
Cluster Profiles:

Cluster 0: Largest group (3,258 customers) with moderate purchasing behavior.
Cluster 1: Dormant customers (1,108) with minimal engagement.
Cluster 2: VIP customers (6) contributing significantly to revenue.
Sales Trends:

Peak activity during November and December.
Most orders placed mid-week and mid-day.
Profitability:

Identified top products with the highest profit margins.
Recommendations
For Moderate-Value Customers (Cluster 0):

Launch loyalty programs.
Personalize marketing campaigns with product recommendations.
For Low-Value Customers (Cluster 1):

Re-engagement campaigns with exclusive discounts or trials.
For High-Value Customers (Cluster 2):

Retention strategies with VIP programs and exclusive perks.
General Strategies:

Cross-selling and up-selling.
Seasonal campaigns during peak periods.
Feedback collection for enhanced customer satisfaction.

# Conclusion
This project highlights the power of RFM analysis and clustering in extracting actionable insights from customer data. These techniques provide a robust foundation for data-driven decision-making in customer relationship management.
