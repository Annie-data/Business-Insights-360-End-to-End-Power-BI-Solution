# Business-Insights-360-End-to-End-Power-BI-Solution
A comprehensive end-to-end Business Intelligence solution built using Power BI to analyze and monitor performance across multiple business functions, including Finance, Sales, Marketing, and Supply Chain.
___
## Business Problem  

Organizations often struggle with fragmented data across departments (Finance, Sales, Marketing, and Supply Chain), leading to:
- Lack of a complete view of business performance.
- Slow, data-driven decision-making due to fragmented insights.
- Difficulty in tracking profitability and operational efficiency

This project solves these challenges by building a centralized Business Intelligence solution that provides a 360-degree view of enterprise performance. [LINK ](https://app.powerbi.com/view?r=eyJrIjoiMTMxNmVjYTEtN2IxMy00MDViLWI4MDYtMjE1M2UxZmVkNDlhIiwidCI6IjkzOGJhZDgxLWU1NWItNGQ2MS04MDliLWIwZGRmMWU1NmM1ZCIsImMiOjEwfQ%3D%3D)
___
## Key Metrics Used

- Gross price (GS$)
- Pre-invoice deductions
- Net Invoice sales
- Post-Invoice deductions
- Net sales (NS$)
- Cost of goods sold (COGS)
- Gross Margin (GM $)
- Net profit
- YTD - Year to Date
- YTG - Year to Go
- Net Error & Absolute Error
- Forecast Accuracy
- Market Share %
___
## Key Insights

- Despite generating $3.7B+ in revenue, the business shows negative profit margins (~14%), indicating high operational costs
- Certain regions and product segments consistently underperform in profitability
- Forecast Accuracy (~81%) reveals inefficiencies in demand planning
- Supply chain risks identified:

&nbsp;&nbsp;&nbsp;&nbsp;**Excess Inventory (EI)** → increased holding costs

&nbsp;&nbsp;&nbsp;&nbsp;**Out of Stock (OOS)** → missed revenue opportunities
- Revenue is concentrated among a few top customers, indicating dependency risk

___
## Dashboard Features

- Multi-domain dashboards: Finance, Sales, Marketing, Supply Chain, Executive View
- KPI tracking with dynamic filters (region, product, customer)
- Time-series trend analysis (YoY, YTD)
- Supply chain performance monitoring (Forecast Accuracy, Risk Analysis)
- Profitability breakdown using waterfall and matrix visuals
- Executive-level summary for quick decision-making

___
## Data Model

Designed using **Star Schema** for performance optimization

**Tables:**

- Fact Tables → Sales, Forecast, Manufacturing Cost, Freight Cost
- Dimension Tables → Customer, Product, Market, Date

___
## Tools & Skills

- SQL
- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- Power Query (ETL)
- Excel
- Business Intelligence & Analytics

___
## Recommendations
Optimize pricing strategies to improve Net Profit %
Improve demand forecasting to increase Forecast Accuracy
Reduce Excess Inventory and Stockouts through better planning
Focus on underperforming regions to improve profitability
Diversify customer base to reduce dependency risk
___
## Live Dashboard
[[Click here to view the interactive dashboard]](https://app.powerbi.com/view?r=eyJrIjoiMTMxNmVjYTEtN2IxMy00MDViLWI4MDYtMjE1M2UxZmVkNDlhIiwidCI6IjkzOGJhZDgxLWU1NWItNGQ2MS04MDliLWIwZGRmMWU1NmM1ZCIsImMiOjEwfQ%3D%3D)

___
## Preview
📊 Dashboard
Finance View

<img width="1448" height="812" alt="Image" src="https://github.com/user-attachments/assets/23f85001-a027-4629-81b9-c65f1845d818" />

Sales View

<img width="1450" height="812" alt="Image" src="https://github.com/user-attachments/assets/fe3c158c-c477-469e-a5c0-ace72e6c1e4d" />

Marketing View

<img width="1450" height="814" alt="Image" src="https://github.com/user-attachments/assets/4ec2e0e8-c64f-4b8b-a9d3-fbec39d09bee" />

Supply Chain View

<img width="1446" height="812" alt="Image" src="https://github.com/user-attachments/assets/87d2ee3a-c68a-4b0e-b94f-2f05c9a9e8d3" />

Executive View

<img width="1453" height="810" alt="Image" src="https://github.com/user-attachments/assets/88d16f0b-6df9-4e85-89be-7642b29d7fee" />

Data Model

<img width="663" height="799" alt="Image" src="https://github.com/user-attachments/assets/962d8f39-a06c-47b9-b9fd-f016d92c1cb9" />

___
## Data Modeling Approach
Designed a star schema model for efficient querying and scalability
Established relationships between fact and dimension tables
Created calculated measures using DAX for dynamic KPI tracking
Implemented time intelligence functions (YoY, YTD analysis)
___
## What I Learned
How to design end-to-end BI solutions across multiple business domains
Importance of data modeling for performance optimization
Using DAX to create context-aware and dynamic KPIs
Translating raw data into actionable business insights
Understanding real-world challenges in profitability and supply chain analytics

___
## Author
Nhi NGUYEN (Annie)
