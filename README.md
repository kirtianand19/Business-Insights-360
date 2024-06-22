```markdown
# Business Insights 360

## Project Overview

AtliQ Hardware, experiencing rapid growth, has embarked on implementing data analytics using Power BI to gain a competitive edge and drive data-driven decisions. This project aims to address stakeholder questions across finance, sales, marketing, and supply chain.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZjMwNGQ4NzQtOGU1NS00YTM2LTg0ZGMtZGQ2NjBmYTU1OTNjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for optimization)
- **Project Charter File**

## Power BI Techniques Learned

- Key questions to ask before starting a project
- Creating calculated columns and measures using DAX
- Data modeling
- Using Bookmarks and Page Navigation
- Error prevention using the Divide function
- Creating a date table using M language
- Dynamic titles based on filters
- KPI indicators and conditional formatting
- Data validation techniques
- Power BI Services: Publishing, auto-refresh setup, app creation, collaboration, and access permissions

## Business Terms

- Gross Price, Net Invoice Sale, Gross Margin, Net Sales, Net Profit
- COGS (Cost of Goods Sold), YTD (Year to Date), YTG (Year to Go)
- Sales Channels: Direct, Retailer, Distributor

## Company Background

AtliQ Hardware, a global seller of computer and accessories, operates through Retailers, Direct, and Distributors channels. Facing competition with data analytics, AtliQ aims to build an analytics team for better insights and decisions.

### Key Questions Before Starting the Dashboard

1. What is the objective of building this Power BI dashboard?
2. How will the success of this project be measured?
3. What is the project timeline?
4. Are stakeholders expecting a preview before the final release?
5. What are stakeholders' hopes and fears regarding this project?
6. Who will use this dashboard and for what purpose?
7. What are the expectations at project completion?
8. What potential issues might arise during the project?
9. What resources and data are needed?
10. Are there any design and view preferences from stakeholders?

## Dataset Overview

### Dimension Tables

- **dim_customer:** 27 markets, 75 customers, 2 platforms (Brick & Mortar, E-commerce), 3 channels (Retailer, Direct, Distributors)
- **dim_market:** 27 markets, 7 sub-zones, 4 regions (APAC, EU, NA, LATAM)
- **dim_product:** 3 divisions (P&A, PC, N&S), 14 categories

### Fact Tables

- **fact_forecast_monthly:** Forecast customer needs to enhance satisfaction and reduce storage costs
- **fact_sales_monthly:** Monthly sales data

### Additional Tables

- **freight_cost:** Travel and other costs by market and fiscal year
- **gross_price:** Gross prices by product code
- **manufacturing_cost:** Manufacturing costs by product code and year
- **pre_invoice_deductions, post_invoice_deductions:** Deduction details by customer and year

## Data Modeling

- Followed Snowflake schema for efficient data modeling. Refer to this [blog](https://addendanalytics.com/blog/data-modelling-best-practices/) for best practices.

---

Check out the [Codebasics Power BI Course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project) for more details on how this project was developed.
```

![Data Model](https://github.com/kirtianand19/Business-Insights-360/assets/138418920/b03f1d73-ad04-4abe-86ba-55838fe66d57)

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button 

- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Info
- Support


## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.

