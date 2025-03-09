#E-commerce Customers Segmentation Project

Project Overview:

This project focuses on segmenting customers based on their transactional behavior and demographics data using unsupervised machine learning techniques. The goal is to identify distinct customer groups to enable targeted marketing strategies that enhance customer loyalty and satisfaction.

Dataset:

The dataset contains the following tables:

Customers: Customer details including gender and city.

Genders: Gender identification details.

Cities: Information about customer cities.

Transactions: Data related to customer transactions and coupon usage.

Branches: Data about merchant branches.

Merchants: Data about merchants.

Project Steps:

1. Data Preprocessing:

Loaded and merged different datasets (customers, genders, cities, transactions).

Aggregated transactional data (total transactions, burned coupons).

Encoded categorical data using One-hot encoding.

2. Feature Selection:

Selected key features for segmentation:

Gender

City

Total number of transactions

Number of burned coupons

3. Model Development:

Applied K-Means clustering algorithm.

Determined the optimal number of clusters (k=2) using Silhouette Score.

4. Model Evaluation:

Achieved highest silhouette score (0.39) at k=2 clusters.

5. Segments Analysis:

Segment 0: Moderate engagement, with an average of approximately 3.5 transactions and around 1.6 burned coupons.

Recommendation: Targeted periodic discounts and promotions to enhance engagement.

Segment 1: High engagement, averaging about 7 transactions and 4 burned coupons.

Recommendation: Offer loyalty programs and exclusive deals to sustain customer loyalty and satisfaction.

6. Visualizations & Dashboard:

Provided visualizations for easy interpretation of clusters.

Illustrated demographic distribution clearly through bar plots.

Conclusion:

The segmentation clearly identified two main groups, enabling tailored marketing strategies to optimize customer satisfaction and engagement.a-Science-2
