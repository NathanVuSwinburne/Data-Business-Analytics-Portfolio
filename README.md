# Data & Business Analytics Portfolio

This portfolio demonstrates business intelligence, dashboard development, data modelling, and business insight generation using Power BI and Tableau.

## Featured Tableau Project

### Procurement Analytics Dashboard

An interactive procurement analytics solution covering executive KPIs, cost saving opportunities, supplier concentration, and supply chain risk.

**[View the Procurement Analytics Dashboard repository](https://github.com/NathanVuSwinburne/procurement-analytics-dashboard-tableau/)**

The dedicated repository contains the Tableau workbook documentation, dashboard previews, data preparation process, business insights, recommendations, and infographic.

## Power BI Projects

# 1. HR Attrition Dashboard

## User Story

The Head of HR required a comprehensive interactive dashboard for analysing employees and answering business questions about:

* Employee demographics, including race, education, age, and gender
* Workforce size, attrition rate, and hiring trends
* Performance review timelines and satisfaction ratings
* Groups most affected by attrition and potential retention strategies

The dashboard allows executives to filter by department, gender, age group, year, and attrition status. It provides both an executive overview and detailed analysis to support workforce decisions.

**[View the interactive report](https://app.powerbi.com/view?r=eyJrIjoiY2M0N2U2NGQtM2E5NC00ODc3LThkMTAtODAxMjFiZDBlNGE5IiwidCI6ImRmN2Y3NTc5LTNlOWMtNGE3ZS1iODQ0LTQyMDI4MGY1Mzg1OSIsImMiOjEwfQ%3D%3D&pageName=23985c93ca4941285647)**

## Dashboard Snapshots

### Employee Overview

<img width="1413" height="793" alt="HR employee overview dashboard" src="https://github.com/user-attachments/assets/aeb5d855-0155-4b9c-baf5-2a9c9ba1e0e2" />

### Demographics

<img width="1416" height="790" alt="HR demographics dashboard" src="https://github.com/user-attachments/assets/5f2aa328-2e92-48d5-bd2b-4ec3a8abe1e6" />

### Attrition Analysis

<img width="1413" height="796" alt="HR attrition analysis dashboard" src="https://github.com/user-attachments/assets/468f08d8-a6f1-42c6-81d2-baf57ad04062" />

### Performance Tracking

<img width="1413" height="792" alt="HR performance tracking dashboard" src="https://github.com/user-attachments/assets/9104f729-3681-450c-944b-50d8648aa884" />

### Data Modelling with a Star Schema

<img width="832" height="717" alt="HR attrition star schema" src="https://github.com/user-attachments/assets/f97cca18-18d0-465a-8807-00a8ba98f11b" />

## Key Insights

* Total employees: **1,470**
* Attrition rate: **16.12%**, with the highest departmental rate in Sales at **20.63%**
* Employees aged **20 to 29** formed the largest age group and recorded the most resignations
* Employees without stock options showed higher attrition
* White employees had the highest average salary at **$115,000**, while the Other group had the lowest at **$101,000**

## Recommendations

* Introduce stock options or performance bonuses for eligible employees
* Strengthen career development, mentorship, and training for younger employees
* Prioritise retention initiatives within Sales and HR
* Monitor job satisfaction and employee self ratings for declining trends

# 2. Contoso Sales & Customer Service Dashboard

## User Story

The CEO of the Contoso ecommerce business required a single interactive dashboard for understanding sales performance and customer service efficiency.

The dashboard was designed to:

* Track open, won, and lost opportunities against revenue targets
* Identify the products, campaigns, and regions generating the most revenue
* Analyse factors affecting won and lost deals
* Identify the highest revenue clients for retention initiatives
* Monitor customer satisfaction, escalation rate, SLA compliance, and resolution time
* Highlight open and high priority cases requiring attention

Executives can filter results by sales owner, manager, region, and product category to move between company level KPIs and detailed analysis.

Two report visuals are not supported by the public Power BI web version and are represented by static screenshots. Download the PBIX file for the complete interactive report.

**[Download the Contoso PBIX file](https://github.com/NathanVuSwinburne/Data-Business-Analytics-Portfolio/blob/main/ContosoDashboardFinal.pbix)**

**[View the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTk1ZjhiMWItOTVhYS00NjhlLWIyMDAtYjU1N2M4NTdmN2M2IiwidCI6ImRmN2Y3NTc5LTNlOWMtNGE3ZS1iODQ0LTQyMDI4MGY1Mzg1OSIsImMiOjEwfQ%3D%3D&pageName=ReportSection909ea50e7939156807d6)**

## Dashboard Snapshots

### Sales Overview

<img width="1148" height="645" alt="Contoso sales overview dashboard" src="https://github.com/user-attachments/assets/3e352e8e-8ff6-4ede-aff1-4c9a835f3053" />

### Customer Service Analysis

<img width="1102" height="626" alt="Contoso customer service dashboard" src="https://github.com/user-attachments/assets/37e73cae-5a05-470e-a4a1-38c754dcf5e1" />

### Factors Driving Won and Lost Deals

<img width="1128" height="626" alt="Contoso deal outcome analysis" src="https://github.com/user-attachments/assets/a86f8871-53c7-4ad5-9066-933b2f8e621a" />

### Revenue Performance and Contributors

<img width="1152" height="648" alt="Contoso revenue analysis dashboard" src="https://github.com/user-attachments/assets/d92969d9-fc39-4da5-9066-933b2f8e621a" />

### Data Modelling with a Snowflake Schema

<img width="1001" height="688" alt="Contoso snowflake schema" src="https://github.com/user-attachments/assets/a361dc9a-f0f4-49ec-9c11-957d89e59785" />

## Key Insights

* Close rate: **64.5%** across **12,346 opportunities**
* Highest monthly revenue: **$1.6 million** in July 2020 and January 2021
* Highest revenue products: Design App at **$6.1 million**, Stand up Desk at **$4.5 million**, and Tablets at **$4.1 million**
* Email campaigns generated the highest potential sales value at **$3.3 million**
* Abbott Inc. and Abercathy & Sons were leading revenue contributors
* Average customer satisfaction was **4.27**, escalation rate was **16%**, and SLA compliance was **76%**

## Recommendations

* Prioritise high revenue products in sales and inventory planning
* Expand email marketing campaigns based on their potential sales value
* Develop retention initiatives for leading revenue clients
* Reduce customer service resolution times and escalation rates
* Prioritise open and high severity cases

## Tech Stack

* **Power BI Desktop and Power Query:** Data cleaning and transformation
* **DAX measures:** Revenue, close rate, customer satisfaction, and service KPIs
* **Data modelling:** Star and snowflake schemas supporting HR, sales, and customer service reporting
* **Interactive reporting:** Filters, drilldowns, decomposition trees, and key influencer analysis

## Project Files

* **[HR Attrition Dashboard PBIX](https://github.com/NathanVuSwinburne/Data-Business-Analytics-Portfolio/blob/main/HR%20Attrition%20Dashboard.pbix):** HR analytics report
* **[Contoso Dashboard PBIX](https://github.com/NathanVuSwinburne/Data-Business-Analytics-Portfolio/blob/main/ContosoDashboardFinal.pbix):** Sales and customer service report
* **README.md:** Project documentation

## Author

**Nathan Vu**

[LinkedIn Profile](https://www.linkedin.com/in/nathanvu091005/) | [Portfolio Website](https://www.notion.so/Data-Analytics-Data-Science-Portfolio-241e0c4d77f680e7b8a3f2bd4d54a1d5?source=copy_link)

## What I Learned

* Data modelling decisions (star vs snowflake schema) have a significant impact on DAX performance and filter propagation — getting the model right before writing measures saves substantial rework
* Power Query transformations should be documented step-by-step; unnamed applied steps make pipelines impossible to audit or hand over
* Dashboard layout is an analytical choice, not just a design one — where you place a slicer determines which questions users can answer without help
* Correlating KPIs across business functions (e.g. service SLA breach → next-quarter satisfaction) requires careful date alignment and is easy to get wrong with naive joins
