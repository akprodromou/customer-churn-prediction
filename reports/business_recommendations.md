## Business Action Recommendations

Based on our exploratory data analysis, prediction modeling, and churn investigation, the following steps to reduce churn and improve customer retention are proposed:

**1. Address High Churn in Key Cities (San Diego & Escondido)**

**Finding:**
* San Diego has the highest churn rate (64.9%) and highest average Monthly Charge (72.02 USD).
* Escondido also experiences high churn (31.3%) with high Monthly Charges (67.88 USD).
* These cities also have a lower percentage of long-term contracts (One-Year & Two-Year).

**Recommendations:**
* Offer discounts for long-term contracts (One-Year & Two-Year) to encourage customer commitment.
* Identify high-churn customers and offer loyalty perks.
* Investigate regional service quality issues, e.g. conduct customer satisfaction surveys to determine if poor service quality is a driver of churn.
* Research local competitors' pricing and service offerings. Consider matching competitor pricing or improving value-added services.

**2. Pricing Optimization for Monthly Charge Segments**

**Finding:**
* Customers with higher Monthly Charges churn at significantly higher rates.
* "Low-spend" customers (<40 USD) have lower churn, while "high-spend" customers (>80 USD) are more likely to leave.

**Recommendations:**
* Introduce personalized retention offers for high spenders.
* Offer premium customer support for high-paying customers.
* Are premium plans priced too high compared to competitors? Re-evaluate pricing strategy for premium plans.
* Consider adding additional benefits (higher speeds, priority customer support, free streaming services) to justify the cost.
* Make limited-time offers that increase commitment (e.g., "Sign a 2-year contract now and get 10% off your monthly bill").

**3. Increase Long-Term Contract Engagement**

**Finding:**
* Churn is significantly lower for customers on long-term contracts (one-year & two-year).
* High-churn cities have a lower percentage of long-term contracts.

**Recommendations:**
* Expand incentives for long-term contracts.
* Offer stronger discounts for committing to a one-year or two-year contract or other benefits (e.g. priority support, free device upgrades etc.).
* Target month-to-month customers with proactive renewal offers.

**4. Addressing High Churn Among Senior Customers**

**Finding:**
* Seniors (55+) have the highest churn rate at 32.5%, significantly higher than middle-aged (24.2%) and young customers (22.4%).

**Recommendations:**
* Dedicated customer support for seniors: Many older customers may prefer phone-based or in-person support rather than digital self-service tools.
* Senior-friendly product bundles: Offer simplified internet + phone service plans with clear pricing and easy access to support.

**5. Using Referrals & Family Status to Reduce Churn**

**Finding:**
* Customers with referrals are less likely to churn.
* Customers with dependents tend to be more stable, likely due to shared family usage.

**Recommendations:**
* Offer better incentives for both referrers and new customers (e.g., discounts, service upgrades).
* Implement a tiered referral program where customers earn increasing rewards for multiple successful referrals.
* Employ family discounts or bundle offers that incentivize customers to add dependents to their plan.
* Offer family-friendly support services (e.g., parental controls, joint account management).

**6. Monitor Client Satisfaction for Future Churn Prevention**

**Finding:**
* The model used in the analysis performed well in predicting churn (~83% accuracy using Random Forest). Satisfaction Score was a major predictor (it was removed for business actionability). The model showed that Monthly Charge, Age, and City Frequency significantly impact churn.

**Recommendations:**
* Deploy churn prediction in real-time customer, focusing in the clients highlighted in this analysis.
* Based on real-time satisfaction scores, use the model on low satisfaction clients to investigate / confirm the aforementioned findings, and work on improvements.
* Use retention strategies (e.g., targeted offers, priority support) for flagged customers.
* Integrate churn insights into marketing and sales strategies.