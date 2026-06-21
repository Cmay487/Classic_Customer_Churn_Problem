# Telco Customer Churn Project

## The problem
Telco is experiencing a customer churn rate of 26.54%. This project identifies the highest risk customer segments, quantifies their commercial value, and deploys a predictive ML model to enable proactive retention.


## Summary of Findings

The randonly sampled customers have a Churn proportion of 26.54% with a Standard Error of 0.63% - We have a reliable proportion value due to a low Standard Error value.

At the 95% confidence interval, Telco should expect 25 to 28 customers to churn per 100 sampled customers.

Monthly charges have some impact on customer churn, but it has a small part to play as these charges are driven by services the customer pays for.

Fiber Optic customers have the highest risk of churning as, by applying a Binomial Distribution, there is an 8% probability that 42 customers will churn in 100 randomly sampled customers, while the other internet services showed a statistical impossibility of this happening in their groups.

When I delved deeper into Fiber Optic Customers to understand the "Why", the answer was simple - The churned customers typically had no or a small amount of add-ons of the wrong variety (Such as Streaming Films and TV). This means that these add-ons appeared to be a strong predictive feature for Fiber Optic customer churn depending on what add-on their purchased.

The total active customers at risk of churning are 208, where their lifetime value equates to £332,002 and a monthly income of £16,476.55, which is 13.84% of their active Fiber Optic customerbase.

**For Telco to reduce their customer churn, they should do the following:**

For the Fiber Optic customers without Online Security, they should be offered this service at a discounted price to entice them.

Online Security should be prioritised as an upsell add-on for new Fiber Optic customers.

Streaming Services should be upsold only if the customer has signed up to Online Security, Tech Support and Online Backup.
