# Business Insights 360

## Project Overview

AtliQ Hardware has been growing rapidly in recent years and has decided to implement data analytics using Power BI to surpass competitors and make data-driven decisions. This project aims to provide answers to stakeholder questions across finance, sales, marketing, and supply chain.

I worked on this project by following the Codebasics Power BI Course. The link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project).

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZjMwNGQ4NzQtOGU1NS00YTM2LTg0ZGMtZGQ2NjBmYTU1OTNjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for optimizing the report)
- **Project Charter File**

## Power BI Techniques Learned

- Key questions to ask before starting a project
- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Using bookmarks to switch between visuals
- Page navigation with buttons
- Using the divide function to prevent division by zero errors
- Creating date tables using M language
- Dynamic titles based on applied filters
- Using KPI indicators
- Conditional formatting with icons or background colors
- Data validation techniques
- Power BI services: publishing reports, setting up personal gateways for auto-refresh, app creation, collaboration, workspace, and access permissions

## Business Terms

- **Gross Price**
- **Pre-Invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS (Cost of Goods Sold)**
- **YTD (Year to Date)**
- **YTG (Year to Go)**
- **Direct**
- **Retailer**
- **Distributors**
- **Consumer**

## Company Background

AtliQ Hardware, a company that has grown significantly in recent years, operates globally and sells computers and accessories through three channels:

- Retailers
- Direct
- Distributors

The company recently faced a loss from opening a store in America based on surveys, intuition, and some Excel analysis. Competitors have analytics teams for data-driven decisions, prompting AtliQ to build its own analytics team for future insights and decisions.

### Key Questions Before Starting the Dashboard

1. What is the objective of building this Power BI dashboard?
2. How will the success of this project be measured?
3. What is the project timeline?
4. Are stakeholders expecting a preview before the final release?
5. What are stakeholders' hopes for this project?
6. What are stakeholders' fears regarding this dashboard?
7. Who will use this dashboard and for what purpose?
8. What are the expectations upon project completion?
9. What potential issues might arise during the project?
10. What resources and data are needed to build this dashboard?
11. Are there any design and view preferences from stakeholders?

After the project kickoff meetings, the data engineering team provided the requested data for analysis.

### Dataset Overview

Understanding the available data is crucial before analysis. Here’s a summary:

**Dimension Tables:** Contain static data like customer and product details.

**Fact Tables:** Contain transaction data.

#### gdb041:

- **dim_customer**
  - 27 distinct markets (e.g., India, USA, Spain)
  - 75 distinct customers across markets
  - 2 types of platforms: Brick & Mortar (physical/offline) and E-commerce (online)
  - 3 channels: Retailer, Direct, Distributors
- **dim_market**
  - 27 distinct markets
  - 7 sub-zones
  - 4 regions: APAC, EU, NA, LATAM
- **dim_product**
  - Divisions:
    - P & A: Peripherals, Accessories
    - PC: Notebook, Desktop
    - N & S: Networking, Storage
  - 14 different categories (e.g., Internal HDD, keyboard)
  - Various product variants

#### Fact Tables:

- **fact_forecast_monthly**
  - Forecasts customer needs to enhance satisfaction and reduce storage costs
  - Denormalized for analytical purposes
  - Dates replaced by the start date of the month
  - Contains forecast quantity at the end
- **fact_sales_monthly**
  - Similar to the forecast table but with sold quantities instead of forecast values

#### gdb056:

- **freight_cost**
  - Travel and other costs for each market with fiscal year
- **gross_price**
  - Gross prices by product code
- **manufacturing_cost**
  - Manufacturing costs by product code and year
- **pre_invoice_deductions**
  - Pre-invoice deductions percentage by customer and year
- **post_invoice_deductions**
  - Post-invoice and other deductions details

## Importing Data into Power BI

- As the database is MySQL, import datasets from the MySQL database to Power BI using database access credentials.

## Data Model

- Data modeling is crucial and forms the foundation of the report. All visuals are built upon the data model.
- Poor data modeling affects the overall performance of the report.
- Follow best practices for data modeling. Refer to this [Blog](https://addendanalytics.com/blog/data-modelling-best-practices/) for more information.
- This project follows the Snowflake data modeling method.

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

## Overall Report View

![Overall Report.gif](https://github.com/kirtianand19/Business-Insights-360/assets/138418920/57d761b9-0a3e-42bd-80ff-36745f505b5b)

## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.

