# Customer Churn Analysis

This project involves a data-driven analysis of customer churn using Power BI, aiming to identify key factors contributing to customer attrition and to offer strategies for improving customer retention.

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Objective](#objective)
3. [Dataset Overview](#dataset-overview)
4. [Analysis and Insights](#analysis-and-insights)
   - [Churn Rate and General Overview](#churn-rate-and-general-overview)
   - [Churn by Tenure](#churn-by-tenure)
   - [Churn by Contract Type](#churn-by-contract-type)
   - [Churn by Payment Method](#churn-by-payment-method)
   - [Churn by Customer Demographics](#churn-by-customer-demographics)
   - [Churn by Service Usage](#churn-by-service-usage)
5. [Key Results](#key-results)
6. [Recommendations](#recommendations)
7. [Conclusion](#conclusion)

![dash 1](https://github.com/shadmanshaikh/customer-churn-analysis/blob/main/1.png)

![dash 2](https://github.com/shadmanshaikh/customer-churn-analysis/blob/main/2.png)

## Problem Statement

Customer churn, defined as the percentage of customers who discontinue their service, is a critical business metric in subscription-based industries. High churn rates can negatively impact revenue and growth, making it crucial for companies to understand the underlying causes of customer attrition and develop effective retention strategies. The goal of this analysis is to examine customer data, identify key factors contributing to churn, and recommend actionable insights to reduce customer attrition.

## Objective

The primary objectives of this analysis are to:

- Understand the patterns and reasons behind customer churn.
- Identify the customer demographics and contract types that exhibit the highest churn rates.
- Provide insights into services, billing, and contract models that influence customer retention.
- Recommend strategies to improve customer retention by focusing on vulnerable segments.

## Dataset Overview

The dataset contains records for 7,043 customers, with 21 attributes related to customer demographics, service usage, billing, and contract details. The key fields include:

- **Customer Information**: Gender, SeniorCitizen status, Partner status, Dependents.
- **Services Subscribed**: PhoneService, MultipleLines, InternetService, StreamingTV, etc.
- **Contract Type**: Month-to-month, one year, two years.
- **Payment Method and Billing Information**: MonthlyCharges, TotalCharges.
- **Churn Flag**: Indicates whether the customer has discontinued the service.

## Analysis and Insights

### Churn Rate and General Overview

- **Total Customers**: 7,043
- **Number of Customers Who Have Left the Service**: 1,869
- **Overall Churn Rate**: 26.54%

This indicates that more than a quarter of the customers have discontinued their subscriptions.

### Churn by Tenure

- Customers with shorter tenures (1-12 months) have a higher churn rate.
- 30% of customers churn after their first month of service, suggesting dissatisfaction or misalignment with expectations during the initial phase.
- After approximately 24 months, churn rates significantly decrease, indicating that long-term customers are more likely to remain loyal.

### Churn by Contract Type

- **Month-to-Month Contracts**: Exhibit the highest churn rates (73.4% of churn comes from customers with month-to-month plans).
- **1-Year Contracts**: Significantly lower churn rate (26.6%).
- **2-Year Contracts**: Lowest churn rate (2.83%).

These findings suggest that offering incentives for longer-term contracts may improve retention.

### Churn by Payment Method

- Customers who pay through monthly electronic checks are more likely to churn compared to those using automatic bank transfers or mailed checks.
- 40% of the churned customers use monthly payment plans, indicating that these customers are more price-sensitive or dissatisfied with the value of the service.

### Churn by Customer Demographics

- **Dependents**: Customers without dependents churn more frequently, representing a higher churn percentage compared to customers with dependents, who show more stability.
- **Gender**: Both male and female customers show relatively similar churn rates, with no significant difference in churn patterns based on gender.
- **Senior Citizens**: Non-senior citizens (60%) make up the majority of churn, suggesting that this group may require tailored marketing strategies to enhance retention.

### Churn by Service Usage

- Customers using additional services like online security, tech support, and streaming TV churn less frequently, suggesting that bundled services may lead to higher retention due to the increased value perceived by customers.
- Phone service and multiple lines do not seem to have a significant impact on churn rates.

## Key Results

- **Contract Type**: Customers on longer-term contracts (1-year or 2-year) have higher retention rates. This insight has led to a recommendation to shift subscription models to focus on promoting longer-term contracts.
- **First-Month Churn**: 30% of customers who churn do so after the first month, suggesting the need for improving customer onboarding and initial service satisfaction.

## Recommendations

- **Promote Longer-Term Contracts**: Encourage customers to opt for longer-term contracts by offering incentives such as discounts or added benefits.
- **Enhance Onboarding Experience**: Develop comprehensive onboarding programs to ensure customers understand and can effectively use the services from the outset.
- **Offer Bundled Services**: Create bundled service packages that provide additional value, as customers using multiple services are less likely to churn.
- **Monitor Payment Methods**: Pay attention to customers using monthly electronic checks and consider offering alternative payment options or incentives to switch to more stable payment methods.
- **Targeted Retention Strategies**: Focus retention efforts on demographics more likely to churn, such as customers without dependents and non-senior citizens, by tailoring marketing and support initiatives to their specific needs.

## Conclusion

By analyzing customer demographics, contract types, payment methods, and service usage patterns, this analysis identifies key factors contributing to customer churn. Implementing the recommended strategies can help reduce churn rates, improve customer satisfaction, and enhance overall business performance.
