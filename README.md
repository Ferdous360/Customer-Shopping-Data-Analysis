# Customer-Shopping-Data-Analysis
Comprehensive data cleaning pipeline and behavioral analysis of 90,000+ shopping transactions using Python, Pandas, and Seaborn.
# Retail Analytics: End-to-End Data Cleaning & Consumer Insights
**Author:** Ferdous Ahmed  
**Context:** Macquarie University - Business Analytics  

This repository showcases a complete data lifecycle: transforming a corrupted raw retail dataset into a validated source for strategic business intelligence.
### 🧹 Data Cleansing Workflow
Because real-world data is rarely perfect, this project documents the step-by-step resolution of data integrity issues found in the raw source (`ref_shopping_data.csv`):

* **Duplicate Management:** Identified and removed redundant `customer_id` entries to ensure transaction accuracy.
* **Categorical Standardization:** Fixed misspellings and naming inconsistencies (e.g., standardizing "Mall of Istanbul").
* **Structural Validation:** Standardized `invoice_no` prefixes and converted `invoice_date` to proper datetime objects for trend analysis.
* **Outlier Audit:** Utilized Boxplots to verify that `price` and `quantity` variables fell within logical industry ranges.
### 📊 Strategic Business Insights
After processing 90,000+ transactions, the following core insights were derived:

* **High-Value Demographics:** The **36-45 age group** emerged as the primary revenue driver, followed closely by the 26-35 and 46-55 segments.
* **Product Performance:** **Clothing** is the dominant category in both volume and revenue. **Technology and Shoes** represent "High-Value" opportunities with higher average transaction prices.
* **Geographic Hubs:** **Mall of Istanbul** and **Kanyon** are the top-performing locations, while smaller malls (like Emaar Square) represent growth opportunities for targeted promotions.
* **Gender Trends:** Analysis revealed that spending behavior is remarkably consistent across genders, suggesting that broad-reach marketing campaigns may be more cost-effective than gender-segregated ones.
### 💡 Strategic Recommendations
1.  **Loyalty Focus:** Launch targeted loyalty programs for the **26-55 demographic**, as they represent the most stable and high-spending customer base.
2.  **Payment Optimization:** Since digital payments are preferred, implement "Flash Sales" or rewards for card users to further reduce cash-handling friction.
3.  **Inventory Alignment:** Prioritize inventory turnover in **Clothing and Technology** at top-performing malls (Istanbul/Kanyon) to maximize ROI.
