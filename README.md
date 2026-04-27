# CLV_Churn_Prediction-
#  Customer 360: Lifetime Value (CLV) & Churn Intelligence
**Objective:** Identifying high-value customers and preventing revenue churn.

Retaining a customer is 5x cheaper than acquiring a new one. This dual-engine pipeline predicts which customers are about to leave and estimates how much they are worth in the long run.

###  Technical Implementation:
- **Churn Engine:** XGBoost Classifier with SMOTE for handling class imbalance (Churn vs. Stay).
- **CLV Regressor:** High-precision regression to estimate future cash flows per user.
- **Customer Segmentation:** RFM-based KMeans clustering to identify "Champions," "Loyalists," and "At-Risk" segments.

###  Business Impact:
- **Revenue Protection:** Segments the "Critical Risk" revenue (e.g., $4.4M identified) for immediate win-back campaigns.
- **Precision Marketing:** Allows marketing teams to spend their budget only on high-CLV segments.
