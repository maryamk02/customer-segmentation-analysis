# Customer Segmentation Analysis

Analysis of 500,000+ retail transactions to segment customers by purchase frequency and identify revenue opportunities.

## Dataset

UCI Online Retail Dataset - Transaction data from a UK-based online retailer (2010-2011)

## Objective

Segment customers by purchase frequency and understand what drives customer lifetime value.

## Key Findings

**Total Customers Analysed:** 4,339

**Customer Breakdown:**
- Frequent customers (6+ orders): 4,040 (93%)
- Occasional customers (2-5 orders): 228 (5%)
- One-time customers (1 order): 71 (2%)

**Average Revenue Per Customer:**
- Frequent: £4,316.08
- Occasional: £1,262.74
- One-time: £1,379.68

## Insights

**1. Exceptional customer loyalty**  
93% of customers are frequent buyers (6+ orders), indicating strong product-market fit and high customer satisfaction. This retention rate is significantly above typical retail benchmarks.

**2. Frequent customers drive 3.4x more value**  
Frequent buyers spend £4,316 on average compared to £1,263 for occasional customers, a 3.4x difference in lifetime value.

**3. The 228 occasional customers represent an immediate opportunity**  
Moving just 20% into the frequent category could generate approximately £696,000 in additional revenue.

## Business Implications

**Acquisition over retention:** With only 2% one-time buyers, the challenge isn't converting existing customers. Focus on attracting new customers and ensuring first-time buyers have a positive initial experience.

**Replicate what works:** 93% frequency suggests something is driving exceptional loyalty. Investigate which products, experiences, or touchpoints create this retention and apply those insights to acquisition strategy.

**Target occasional buyers:** The 228 occasional customers are already engaged but haven't crossed into frequent territory. Targeted campaigns encouraging a 6th purchase may shift them into the high-value category.

**First 90 days matter:** With so few one-time buyers, either first-time customers quickly become repeat buyers, or those who don't return aren't captured here. Understanding the early post-purchase period is critical.

## Next Steps to Investigate

1. What triggers the second purchase?
2. How does first purchase behaviour differ between frequent and occasional customers?
3. What prevents occasional customers from reaching 6+ orders?
4. Which products correlate with higher repeat purchase rates?
5. How does purchase frequency change over customer lifetime?

## Tools & Methods

- Microsoft Excel for data cleaning and analysis
- Pivot tables for customer segmentation
- IF statements for segment categorisation
- Data validation and filtering for 500k+ row dataset

## Files

- `Online_Retail_Customer_Analysis_Summary.xlsx` - Analysis with pivot tables, charts, and insights
- `Customer_Distribution_Chart.png` - Customer breakdown by segment
- `Customer_Value_Chart.png` - Average spend by customer type

---

*Raw dataset available from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)*
