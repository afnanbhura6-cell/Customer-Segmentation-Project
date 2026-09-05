# Customer-Segmentation-Project
Interactive Power BI dashboard for customer segmentation, behavioral analysis, data cleaning, and business insights.

## Project Objective
The objective of this project is to analyze customer demographics and purchasing behavior, group customers into meaningful spending segments, and provide business recommendations based on the analysis.

## Dataset
The dataset contains 1,003 customer records and includes:
- Customer ID
- Age
- Gender
- Annual Income
- Purchase Frequency
- Average Order Value
- Total Purchase Amount
- Preferred Category
- Discount Usage
- Website Visits
- Customer Rating

## Data Cleaning
The data was cleaned using Power BI Power Query.

- Promoted the first row as column headers.
- Identified missing values in Age, Annual Income, and Customer Rating.
- Replaced missing values using the median of each respective column.
- Removed duplicate records.
- The final dataset contains 1,000 unique records.

## Customer Segmentation
Customers were divided into three spending-based segments:

- High Spender: Total Purchase Amount >= 30,000
- Medium Spender: Total Purchase Amount >= 15,000 and < 30,000
- Low Spender: Total Purchase Amount < 15,000

## Segment Results

| Segment | Customers | Avg Income | Avg Spending | Avg Purchase Frequency |
|---|---:|---:|---:|---:|
| High Spender | 118 | 54,217 | 36,442.60 | 12.35 |
| Medium Spender | 569 | 56,578 | 21,228.52 | 9.36 |
| Low Spender | 313 | 56,312 | 10,516.30 | 6.83 |

## Key Findings

1. High Spenders have the highest average purchase frequency and spending.
2. Medium Spenders are the largest customer segment with 569 customers.
3. Low Spenders have the lowest purchase frequency and total spending.
4. High Spenders do not have the highest average income, suggesting that income alone does not explain customer spending.
5. Purchase behavior is an important factor when identifying valuable customers.

## Business Recommendations

### High Spenders
Focus on customer retention, loyalty programs, premium offers, and personalized recommendations.

### Medium Spenders
Use cross-selling, bundles, personalized offers, and loyalty incentives to increase their spending.

### Low Spenders
Use targeted promotions and engagement campaigns to encourage more frequent purchases.

## Tools Used
- Power BI
- Power Query
- DAX
- Python/Pandas for initial dataset preparation
