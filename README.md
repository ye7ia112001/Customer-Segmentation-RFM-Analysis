🎯 Customer Segmentation using RFM Analysis
📝 Project Overview

This project applies the RFM (Recency, Frequency, Monetary) model to segment customers of an online retail store. By analyzing over 500,000 transactions, I classified customers into distinct groups to help the marketing team design targeted campaigns and improve customer retention.
🚀 Key Features

    Data Preprocessing: Cleaned a massive dataset, handled missing CustomerID values, and filtered out transactions with negative quantities/prices.

    RFM Metrics Calculation: - Recency: Days since the last purchase.

        Frequency: Total number of unique orders.

        Monetary: Total revenue generated per customer.

    RFM Scoring: Assigned scores from 1 to 5 for each metric using quintiles.

    Customer Segmentation: Mapped RFM scores to 10 distinct segments (e.g., Champions, Loyal Customers, At Risk, Hibernating).

    Data Visualization: Created a Treemap to visualize the distribution of customer segments.

🛠️ Tech Stack

    Python (Pandas, NumPy)

    Visualization: Matplotlib, Seaborn, Squarify (for Treemaps)

    Environment: Jupyter Notebook

📊 Business Insights

Based on the analysis of 4,339 unique customers:

    Champions (633): The most valuable group with an average monetary value of 6,857.9 and a very low recency of 5.9 days.

    Hibernating (1,065): The largest segment, consisting of customers who haven't purchased in over 217 days.

    At Risk (580): High-spending customers who haven't returned in 155 days; they require immediate re-engagement.

📂 Project Structure

    online_retail.csv: Raw transactional data.

    RFM_Analysis.ipynb: Complete Python code, from cleaning to visualization.

    README.md: Project documentation.

💡 How to use

    Install dependencies: pip install pandas squarify matplotlib seaborn.

    Run the Jupyter Notebook to generate the RFM table and segments.
