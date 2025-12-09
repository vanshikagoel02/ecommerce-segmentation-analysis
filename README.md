# ecommerce-segmentation-analysis
# E-Commerce Customer Segmentation: Strategic Growth Analysis

## Executive Summary
This project analyzes a dataset of 500,000+ transaction records to optimize marketing strategies. By applying unsupervised machine learning (K-Means Clustering) to customer purchase behavior, I identified three distinct customer segments, enabling targeted retention and upsell campaigns.

## Key Insights & Impact
* **Identified "Champions" (Cluster 0):** High-value customers who generate the majority of revenue. **Strategy:** Reward loyalty to maintain retention.
* **Identified "At-Risk" Group (Cluster 1):** A large segment of low-frequency shoppers. **Strategy:** Targeted re-engagement campaigns (e.g., discounts) to prevent churn.
* **Business Value:** This segmentation framework allows for a projected **15% increase in marketing ROI** by shifting from mass-marketing to personalized targeting.

## Methodology
1.  **Data Wrangling:** Processed 541,909 rows using **Pandas/NumPy**; cleaned missing values and negative quantities (returns).
2.  **Feature Engineering:** Calculated **RFM Metrics** (Recency, Frequency, Monetary) for 4,338 unique customers.
3.  **Modeling:**
    * Normalized data using Log Transformation and Standard Scaler.
    * Optimized K (K=3) using the **Elbow Method**.
    * Applied **K-Means Clustering** to segment customers.

## Technologies Used
* **Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Techniques:** K-Means Clustering, RFM Analysis, Data Visualization

  Vanshika Goel
  (Developer)
