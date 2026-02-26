# Telco-Customer-Churn
End-to-end Machine Learning pipeline to predict customer churn using Random Forest. Features automated data cleaning, exploratory analysis, and class-imbalance handling to drive business retention strategies.
Telco Customer Churn Prediction
Predicting customer attrition to drive retention and revenue growth.

Project Overview
This project addresses a critical business problem: Customer Churn. Using a dataset of over 7,000 telecom customers, I built a machine learning pipeline to identify "high-risk" customers before they leave. By identifying these individuals early, companies can intervene with targeted retention strategies.

Libraries: Pandas (Data Cleaning), Seaborn/Matplotlib (EDA), Scikit-Learn (Machine Learning)

Model: Random Forest Classifier (with Class Balancing)

Key Insights from EDA
The "First Year" Danger Zone: New customers (tenure < 6 months) are significantly more likely to churn.

Contract Power: Customers on "Month-to-Month" contracts represent the highest churn risk compared to those on 1-year or 2-year commitments.

Pricing Pressure: Higher monthly charges correlate with increased attrition rates.

The Machine Learning Solution
Because the dataset was imbalanced (fewer people leave than stay), I implemented a Balanced Random Forest Classifier.

Results:
Accuracy: ~80%

Recall for Churn: Successfully identified 190 out of 238 actual leavers in the test set.

Business Impact: Instead of losing customers silently, the company can now proactively target 80% of potential leavers with loyalty offers.

Top Predictors of Churn
The model identified the following features as the most important when predicting if a customer will leave:

Total Charges (Lifetime value)

Tenure (Customer loyalty)

Monthly Charges (Current bill impact)

Contract Type (Commitment level)
