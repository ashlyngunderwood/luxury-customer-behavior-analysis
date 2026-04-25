# Luxury Customer Behavior Analysis
This project analyzes customer purchasing behavior using transactional retail data to identify high-value customer segments, revenue concentration, and key drivers of customer value.

## Overview
The analysis focuses on understanding how revenue is distributed across customers and what differentiates high-value customers from lower-value segments.

Key areas of analysis include:
- Revenue concentration
- Customer segmentation
- Purchase frequency
- Average order value

## Tools & Technologies
- Python (pandas, numpy, matplotlib)
- Jupyter Notebook
- Tableau (for visualization and dashboarding)

## Data Preparation
- Standardized column names for consistency
- Removed records with missing customer IDs
- Created a revenue metric (Quantity × Price)
- Ensured appropriate data types for analysis

## Customer-Level Analysis
Transaction-level data was aggregated to the customer level to calculate:
- Total revenue per customer
- Purchase frequency
- Average order value

## Customer Segmentation
Customers were segmented into quartiles based on total revenue:
- Low Value
- Lower-Mid
- Upper-Mid
- High Value

## Key Insights
Revenue Concentration:
The top ~10% of customers account for approximately 60% of total revenue, indicating a highly concentrated revenue distribution.

Customer Behavior Differences:
High-value customers demonstrate significantly higher purchase frequency and average order value compared to lower-value segments.

Segment Contribution:
Despite equal distribution of customers across segments, the highest-value segment contributes the majority of total revenue.

## Business Implications
- Retaining high-value customers is critical to maintaining revenue
- Improving the first customer experience can increase repeat purchases
- Loyalty and incentive programs can help increase engagement
- Mid-tier customers represent an opportunity for growth through targeted strategies

## Deliverables
- Jupyter Notebook containing full analysis and methodology
- Tableau dashboard (to be added) for business-facing visualization
