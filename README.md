# Telco Customer Churn Project

## The problem
Telco is experiencing a customer churn rate of 26.54%. This project identifies the highest risk customer segments, quantifies their commercial value, and deploys a predictive ML model to enable proactive retention.

## Methods & Model Performance
**Statistical methods:** 

Confidence intervals · Binomial Distribution · Chi-Squared testing · Simpson's Paradox analysis

**ML pipeline:** 

Feature engineering · CatBoost classifier · RFE feature selection · Stratified cross-validation (class imbalance present) · Hyperparameter tuning

**Model performance:** 

77% accuracy · 72% precision · 56% recall (churn class) · 0.73 macro F1
The final model was "overly-cautious" in identifying due to high number of predicted churned customers, when they were not. However, this solution is the better version if the opposite was true - unable to accurately predict customer churn.


## Summary of Findings

The randomly sampled customers have a churn proportion of 26.54% with a Standard Error of 0.63% — we have a reliable proportion value due to a low Standard Error value.

At the 95% confidence interval, Telco should expect 25 to 28 customers to churn per 100 sampled customers.

Monthly charges have some impact on customer churn, but it has a small part to play as these charges are driven by services the customer pays for.

Fiber Optic customers have the highest risk of churning as, by applying a Binomial Distribution, there is an 8% probability that 42 customers will churn in 100 randomly sampled customers, while the other internet services showed a statistical impossibility of this happening in their groups.

When I delved deeper into Fiber Optic customers to understand the "why", the answer was simple — the churned customers typically had no or a small amount of add-ons of the wrong variety (such as Streaming Films and TV). This means that these add-ons appeared to be a strong predictive feature for Fiber Optic customer churn depending on what add-ons they purchased.

The total active customers at risk of churning are 208, where their lifetime value equates to £332,002 and a monthly income of £16,476.55, which is 13.84% of their active Fiber Optic customer base.
