# Customer-churn-analysis
![image](https://github.com/user-attachments/assets/b61520a3-1f1f-462d-b390-2ca56e66f2c0)

# Customer Churn Analysis

## Table of Contents
1. [Customer Churn](#customer-churn)
2. [Dataset](#dataset)
3. [Business Questions](#business-questions)
4. [Key Findings](#key-findings)

## Customer Churn
Customer churn is measured using the customer churn rate.
Churn Rate = (Lost Customers / Total number of customers) * 100

## Dataset
1. The dataset was taken from Datacamp.
2. The following are the data attributes: 
    - Customer ID
    - Churn Label
    - Churned
    - Account Length (in months)
    - Local Calls
    - Local Mins
    - Intl Calls
    - Intl Mins
    - Intl Active
    - Intl Plan
    - Extra International Charges
    - Customer Service Calls
    - Avg Monthly GB Download
    - GB Download Distribution
    - Unlimited Data Plan
    - Extra Data Charges
    - State
    - Phone Number
    - Gender
    - Age
    - Under 30
    - Senior
    - Group
    - Number of Customers in Group
    - Device Protection & Online Backup
    - Contract Type
    - Payment Method
    - Monthly Charges Bins
    - Monthly Charge
    - Total Charges
    - Churn Category
    - Churn Reason

## Business Questions
1. How does having an international plan affect the average monthly charges? Is there a significant difference in spending?
2. Which payment method is associated with the highest average monthly charges? Is there a correlation between payment method and churn rate?
3. Do customers with higher customer service call counts have a higher average monthly charge? How does this correlate with churn?
4. How do total charges compare across different contract types (Month-to-Month, One Year)? Are longer contracts associated with higher or lower total charges?
5. Which state has the highest churn rate? How does churn distribution vary across different states?
6. Is there a relationship between the number of international calls/minutes and the churn rate? Are customers who use international services more or less likely to churn?
7. How does having device protection and online backup impact churn? Is there a difference in churn rates between customers with and without these services?
8. Segment customers by their monthly charges (e.g., low, medium, high) and compare churn rates across these segments. Are customers with higher charges more or less likely to churn?
9. Calculate the average customer lifetime value for churned vs. non-churned customers. How does churn impact overall customer value?
10. Analyze the GB download patterns across different contract types. Do customers on longer contracts use more or less data? How does this relate to their churn behavior?

## Key Findings
1. Customers without international plans tend to have higher monthly charges.
2. The debit card payment method is associated with the highest average monthly charges of 35.10.
3. Customers who interact with customer service pay an average monthly charge of 36.55.
4. The two-year contract type has the highest total charges of 3,056,047 compared to other contract types.
5. West Virginia has the highest churn rate at 31.7%.
6. The highest churn rate is concentrated in the lowest monthly charge segment (0-100), indicating that customers with very low charges are significantly more likely to churn.
7. Customers without device protection and online backup have a significantly higher churn rate (70.60%) compared to those with these services (29.40%).
8. Customers with medium charges have the highest churn rate (49.39%), indicating that this group is the most likely to churn.
9. Non-churned customers have a significantly higher average customer lifetime value (CLV) compared to churned customers, indicating that non-churned customers contribute much more value over their lifetime.
10. Month-to-month contract holders have the highest churn rate at 87.92% and the highest average monthly GB download at 24,404.
