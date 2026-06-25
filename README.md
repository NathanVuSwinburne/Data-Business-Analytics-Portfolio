# Data & Business Analytics Portfolio

Business intelligence projects demonstrating data modelling, dashboard development, and translating raw data into decisions. Built with Power BI and Tableau.

---

## Projects

### 1. HR Attrition Dashboard — Power BI

**Problem:** HR teams struggle to identify which employee segments are at highest attrition risk and why, making it difficult to target retention efforts effectively.

**Solution:** A Power BI dashboard that segments attrition by department, age group, gender, education level, and job role, with drill-through filtering to surface the highest-risk cohorts.

**Key findings:**
- Overall attrition rate: **16.12%**
- Sales department highest at **20.63%**
- Younger employees (under 30) show disproportionately high attrition rates
- Employees with lower job satisfaction scores leave at 2–3× the rate of satisfied peers

**Methodology:**
- Cleaned and validated HR dataset; resolved duplicate employee records and standardised categorical fields
- Built a star schema in Power BI with an Employee fact table and dimension tables for department, education, and role
- Wrote DAX measures for attrition rate, headcount, and satisfaction score aggregations
- Designed report layout with cross-filtering slicers for department, gender, age band, and year

**[View live dashboard](https://app.powerbi.com/view?r=eyJrIjoiY2M0N2U2NGQtM2E5NC00ODc3LThkMTAtODAxMjFiZDBlNGE5IiwidCI6ImRmN2Y3NTc5LTNlOWMtNGE3ZS1iODQ0LTQyMDI4MGY1Mzg1OSIsImMiOjEwfQ%3D%3D&pageName=23985c93ca4941285647)**

![HR Attrition Dashboard](assets/hr-dashboard.png)
<!-- TODO: Add HR dashboard screenshot -->

---

### 2. Contoso Sales & Customer Service Dashboard — Power BI

**Problem:** Sales leadership needed a single view of opportunity pipeline, revenue performance, and customer satisfaction across product lines and campaigns — pulling from separate source systems.

**Solution:** A unified executive dashboard combining sales pipeline metrics and service KPIs with shared filtering by product, region, and time period.

**Key findings:**
- **64.5%** close rate across 12,346 tracked opportunities
- Average customer satisfaction: **4.27 / 5**
- Top-performing product category drives 38% of total revenue despite representing 22% of pipeline volume
- SLA breach rate correlates with a measurable drop in satisfaction scores in the following quarter

**Methodology:**
- Modelled data using a snowflake schema; linked Opportunities, Products, Campaigns, and Service Tickets fact/dimension tables
- Used Power Query to merge and transform data from two source formats
- DAX measures for win rate, average deal size, SLA compliance rate, and satisfaction trend
- Parameterised date slicer drives all visuals simultaneously

**[View live dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTk1ZjhiMWItOTVhYS00NjhlLWIyMDAtYjU1N2M4NTdmN2M2IiwidCI6ImRmN2Y3NTc5LTNlOWMtNGE3ZS1iODQ0LTQyMDI4MGY1Mzg1OSIsImMiOjEwfQ%3D%3D&pageName=ReportSection909ea50e7939156807d6)**

![Contoso Sales Dashboard](assets/contoso-dashboard.png)
<!-- TODO: Add Contoso dashboard screenshot -->

---

### 3. Procurement Analytics Dashboard — Tableau

**Problem:** Procurement teams lacked visibility into supplier concentration risk, cost trends, and supply chain efficiency at the executive level.

**Solution:** A Tableau dashboard examining executive KPIs, cost optimisation opportunities, supplier risk distribution, and supply chain cycle times.

**Methodology:**
- Cleaned procurement transaction data; standardised supplier names and category codes
- Built calculated fields for spend concentration (Herfindahl index), lead time variance, and cost-per-unit trend
- Designed for executive stakeholders: summary KPIs at top, drill-down detail in lower panels

**[View repository](https://github.com/NathanVuSwinburne/procurement-analytics-dashboard-tableau)**

![Procurement Dashboard](assets/procurement-dashboard.png)
<!-- TODO: Add Tableau dashboard screenshot -->

---

## Tech Stack

| Tool | Used for |
|---|---|
| Power BI Desktop | Dashboard development, DAX measures, report design |
| Power Query (M) | Data transformation, merging, type enforcement |
| DAX | KPI calculations, time intelligence, filter context |
| Tableau | Procurement dashboard |
| Star / snowflake schema | Data modelling for both Power BI projects |

---

## Files

| File | Description |
|---|---|
| `HR Attrition Dashboard.pbix` | Power BI HR workforce analytics report |
| `ContosoDashboardFinal.pbix` | Power BI sales and customer service report |

The Tableau project lives in a [separate repository](https://github.com/NathanVuSwinburne/procurement-analytics-dashboard-tableau).

---

## What I Learned

- Data modelling decisions (star vs snowflake schema) have a significant impact on DAX performance and filter propagation — getting the model right before writing measures saves substantial rework
- Power Query transformations should be documented step-by-step; unnamed applied steps make pipelines impossible to audit or hand over
- Dashboard layout is an analytical choice, not just a design one — where you place a slicer determines which questions users can answer without help
- Correlating KPIs across business functions (e.g. service SLA breach → next-quarter satisfaction) requires careful date alignment and is easy to get wrong with naive joins
