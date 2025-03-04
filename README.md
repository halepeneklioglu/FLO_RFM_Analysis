Project Description: RFM Segmentation for Customer Analytics
Overview
This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis to identify key customer groups for targeted marketing strategies. The dataset contains customer transaction data from an e-commerce company, including online and offline purchases.

Goals
The main objectives of this analysis are:

Understand customer purchasing behavior through exploratory data analysis (EDA).
Calculate RFM metrics to evaluate customer value.
Segment customers based on their purchasing patterns.
Identify high-value customers for targeted marketing campaigns.
Export customer lists for specific marketing strategies.
Key Steps
Data Loading & Preprocessing

Import the dataset.
Check for missing values, data types, and summary statistics.
Create total order and total customer value columns.
Convert date columns to datetime format.
Exploratory Data Analysis (EDA)

Summarize customer behavior by different order channels.
Identify top customers based on total spending and order count.
RFM Calculation

![image](https://github.com/user-attachments/assets/9b194aa0-fc32-471a-854a-8b36c6077e5d)


Define Recency (days since last purchase), Frequency (total purchases), and Monetary (total spending).
Assign RFM scores using quantile-based binning.
Generate an RF score (combination of recency and frequency scores).
Customer Segmentation

![image](https://github.com/user-attachments/assets/55169cf1-6750-4f42-8be1-ff2be9d23e3a)


Apply RFM segmentation rules to categorize customers (e.g., Champions, Loyal Customers, At-Risk, New Customers).
Group and summarize customer behavior per segment.
Exporting Target Customer Lists

Identify high-value customers (Champions, Loyal Customers) interested in specific categories.
Identify at-risk customers for discount-based campaigns.
Save customer IDs to CSV files for further marketing actions.
Expected Outcome
This analysis helps businesses personalize marketing strategies by targeting the right customer segments, optimizing promotions, and increasing customer retention.
