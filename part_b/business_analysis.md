B1
a): The analysis of heart disease data reveals that Max Heart Rate (max_hr) and ST Depression (oldpeak) are the most predictive clinical features. Using a Random Forest classifier, we achieved high sensitivity, which is vital in a medical context to ensure potential cases are not overlooked.

(b): Customer segmentation identified three distinct groups based on spending and visit frequency. Using PCA, we visualized that a significant portion of the variance is driven by Annual Spend and Visit Frequency, allowing us to separate high-value "Power Shoppers" from "Casual Shoppers."

(c): The addition of temporal features, specifically is_month_end, showed that retail volume spikes significantly in the final week of the month. Our Random Forest Regressor handled these seasonal shifts better than the Linear Regression model, providing more accurate inventory forecasts.

B2
In plain language, our machine learning models act as a "navigation system" for both healthcare and retail. For health, the model filters through complex patient data to highlight those who need immediate medical attention. For the retail business, instead of seeing all customers as one group, we now see them as distinct "communities" with different needs. We have also proven that sales aren't random; they follow predictable patterns related to the calendar month and local competition density.

B3
(a): Strategic Promotion Timing: Since the is_month_end feature is a high predictor of sales, the marketing team should schedule "End of Month" clearance events to align with naturally high traffic periods, maximizing revenue.

(b): Tiered Loyalty Programs: The business should create a VIP tier specifically for the "High-Value" cluster identified in our K-Means analysis. For the "Low-Engagement" cluster, we should implement a re-engagement email campaign to increase their monthly visit count.

(c): Clinical Triage Automation: The heart disease model should be integrated into a preliminary screening tool. Patients flagged as "High Risk" based on their max_hr and st_slope should be automatically prioritized for a specialist consultation, reducing the diagnostic wait time for critical cases.
