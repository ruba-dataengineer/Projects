******Data Analytics Approach to Segment Customers Based on Their Interests******************

This project focuses on customer segmentation using RFM analysis (Recency, Frequency, Monetary) to classify customers into loyalty tiers based on their transactional behavior. This analysis helps businesses tailor marketing strategies and improve customer targeting.

**Objective**

To segment customers based on their purchasing behavior and interest using data analytics techniques, enabling businesses to adopt targeted marketing approaches and improve customer retention.

**Project Workflow**

**_Problem Definition_**

Understanding the need for customer segmentation to meet diverse customer needs and increase profitability.

**_Data Collection_**

Retail transaction data sourced from an online store between 2010 and 2011.

**_Data Cleaning & Preprocessing_**

- Removed null and duplicate entries
- Filtered negative or invalid values
- Focused on United Kingdom transactions
- Added total transaction value (TotalAmount)

**_RFM Score Calculation_**

- Recency: Days since last purchase
- Frequency: Number of purchases
- Monetary: Total amount spent

Scored using quartiles and categorized

**_Customer Segmentation_**

Customers were grouped based on RFM scores into:

📀 Platinum
🥇 Gold
🥈 Silver
🥉 Bronze

**Tech Stack**

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV Retail Dataset
