# Customer Shopping Behavior Analysis 

## Project Overview
This project analyzes a retail customer shopping dataset containing 3,900 transactions to uncover purchasing patterns, 
customer segments, and key revenue drivers. The goal was to transform raw transactional data into actionable business insights 
using Python for data preparation, PostgreSQL for business analysis, and Power BI for interactive visualization.


## Business Problem
The retail company wanted to better understand customer shopping behavior in order to:
* Identify high-value customer segments.
* Understand purchasing patterns across demographics.
* Evaluate product and category performance.
* Measure the impact of customer subscriptions.
* Support data-driven marketing and inventory decisions.


## Key Insights
* The Clothing category generated the highest revenue ($104,262), contributing 45% of total revenue, indicating that a significant share of sales depends on a single product category.
* Male customers generated 68% of total revenue ($157,890), while Adult customers (26–45) generated approximately 2.5× more revenue than Young Adults (18–25).
* Non-subscribers accounted for 73% of total revenue, generating $170,436 compared to $62,645 from subscribers.
* Loyal customers represented 80% of the customer base, indicating strong customer retention.
* Gloves received the highest average customer rating (3.86/4), while Shirts recorded the lowest (3.64/4).
* Express Shipping customers recorded the highest average purchase amount ($60.48), suggesting that higher-value orders are associated with faster delivery options.

## Business Recommendations
* Expand investment in the Clothing category while implementing strategies to improve the performance of lower-revenue categories.
* Maintain inventory and promotional focus on high-demand products such as Blouses, while investigating factors affecting Shirt sales.
* Improve lower-rated products by incorporating customer feedback into product development and quality improvement initiatives.
* Develop targeted marketing campaigns for high-value customer segments while increasing engagement among lower-contributing demographics.
* Strengthen the subscription program by offering more compelling incentives to increase customer enrollment.
* Continue investing in loyalty initiatives to retain high-value customers and encourage repeat purchases.
* Evaluate promotional incentives for Express Shipping to determine whether they can increase average order value while maintaining profitability.

## Repository Structure
```text
├── customer_shopping_behaviour/
├── notebooks/
│   └── customer_behaviour.ipynb
├── sql/
│   └── customer_shopping.sql
├── dashboard/
│   └── customer_behaviour_dashboard.pbix
├── documentation/
│   └── Customer Shopping Behavior Analysis.pdf
│   └── Customer Shopping Behavior Analysis.pptx
└── README.md
```

