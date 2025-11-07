# Executive Sales & Performance Dashboard  

![Executive Overview](screenshots/executive.png)

## Executive Summary  
This Power BI dashboard translates sales data into **actionable business intelligence** for a multi-regional retail chain.  

It reveals **growth opportunities, regional dynamics, and customer performance trends** that directly impact revenue, profitability, and marketing efficiency.  
The goal isn’t to visualize data — it’s to **drive strategic decisions** that strengthen market position and improve ROI.  


## Business Context  

The company operates across **four regions** and multiple store locations with diverse product lines.  
While overall sales were growing, leadership lacked clarity on:
- Which regions were most profitable  
- Where performance was stagnating  
- How customer behavior and order patterns were shifting  

This dashboard was designed to provide **a unified business view** — enabling executives to move from *guesswork to data-backed strategy.*


## Business Objectives  

| Objective | Strategic Value |
|:-----------|:----------------|
| Track regional and category-level sales performance | Identify growth and underperforming markets |
| Measure customer acquisition and retention health | Align marketing spend with customer lifetime value |
| Evaluate product performance by sub-category | Optimize pricing and promotion strategies |
| Monitor YoY performance metrics | Support annual planning and forecasting |


##  Key Business Insights  

| KPI | 2025 Value | YoY Change | Business Interpretation |
|:----|------------:|:-----------:|:------------------------|
| **Total Sales** | 10.10M | ⬆️ 28.7% | Strong overall revenue growth – a healthy market position |
| **Total Orders** | 681 | ⬆️ 31.2% | Increased transaction volume – higher market activity |
| **Total Customers** | 500 | ⬆️ 53.8% | Excellent acquisition – successful outreach campaigns |
| **Sales per Customer** | 20.20K | 🔻 16.4% | Customer spend dropped – retention or cross-sell gap |
| **Average Order Value** | 14.83K | 🔻 1.9% | Stable order size – suggests competitive pricing pressure |

**Business Impact:**  
The company is acquiring customers rapidly, but not maximizing value per customer.  
This signals a need for **retention-driven marketing** and **loyalty programs** to lift average revenue per user.


## Regional Performance Insights  

| Region | Sales (M) | % Contribution | Business View |
|:--------|-----------:|:---------------:|:--------------|
| **Eastern** | 3.27 | 32.4% | Core growth engine – strong repeat sales |
| **Central** | 3.13 | 31.0% | Solid performer – consistent YoY improvement |
| **Western** | 1.90 | 18.8% | Stable but slow – opportunity for targeted campaigns |
| **Coast** | 1.79 | 17.7% | Underperforming – needs promotional boost |

**Actionable Takeaway:**  
Double down on Eastern and Central for ROI-driven investments.  
Develop **market penetration plans** for Western and Coast regions.



##  Product Category Analysis  

| Sub-Category | Sales (M) | Business Signal |
|:--------------|-----------:|:----------------|
| Pen | 1.62 | Strong performer, consistent demand |
| Laptop | 1.35 | High-margin category – key revenue driver |
| Stapler | 1.24 | Stable mid-tier performer |
| Tablet | 1.16 | Growth potential with marketing focus |
| Bookcase | 1.12 | Moderate contribution |
| Paper | 0.95 | Volume driver but low profit margin |
| Desk | 0.95 | Solid performer in office markets |
| Phone | 0.90 | Price-sensitive – declining margins |
| Chair | 0.82 | Low traction – candidate for bundling or promo |

**Strategic Opportunity:**  
Invest in **laptops and tablets** as premium growth segments.  
Reprice or reposition **low-margin SKUs** like paper and chairs.  


## Monthly Performance Overview  

The **sales curve** shows strong momentum in Q1–Q2, peaking in **March and April**, followed by a dip in **June–July**.  
This pattern aligns with seasonal purchasing behavior — indicating potential for **mid-year promotional interventions** or **inventory optimization**.

---

## Business Recommendations  

1. **Loyalty & Retention Strategy** – Develop reward programs to increase spend per customer.  
2. **Regional Prioritization** – Focus sales and ad budgets on Eastern and Central, while piloting promotions in Coast.  
3. **Product Portfolio Optimization** – Streamline low-margin SKUs; promote high-margin tech items.  
4. **Seasonal Campaign Planning** – Counteract Q3 dips with limited-time offers.  
5. **BI Integration** – Expand dashboard to track marketing spend vs sales ROI in real time.  

## Technical Implementation  

**Tool:** Power BI  
**Data Source:** Cleaned multi-regional retail dataset (Superstore format)  
**Core DAX Measures:**  
```DAX
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
YoY Sales Growth = DIVIDE(([Total Sales] - [PY Sales]), [PY Sales])
Average Order Value = DIVIDE([Total Sales], DISTINCTCOUNT(Sales[Order ID]))
Customer Count = DISTINCTCOUNT(Sales[Customer ID])
```

## Interactive Features  

The dashboard was designed to enhance decision-making through interactive and dynamic analytics.  
Key interactive features include:

- **Year and City Filters:** Easily switch between time periods and locations for granular insights.  
- **Region and Category Slicers:** Segment data by geography and product type to uncover trends.  
- **Dynamic Visuals:**  
  - KPI Cards for at-a-glance performance metrics  
  - Trend Lines to track revenue and orders over time  
  - Donut and Bar Charts to analyze sales composition and regional contribution  

---

## Business Value Delivered  

**Enhanced Executive Visibility** — Regional and product-level insights presented in a single, unified dashboard.  
**Reduced Reporting Turnaround** — Automated data refreshes replaced manual weekly reports.  
**Improved Decision-Making Speed** — Real-time metrics empower sales and marketing teams to act faster.  
**Strategic Foundation for Forecasting** — Supports demand planning and customer segmentation initiatives.  


## 👨‍💼 About the Creator  

**Samuel Mati**  
*Data Analyst | Business Intelligence Developer | Insight Translator*  

📧 [sammxsaf@gmail.com](mailto:sammxsaf@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/samuel-mati/)  

> “Transforming retail analytics into business clarity.”
