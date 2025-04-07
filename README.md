
# Himalaya Kött & Video Power BI Dashboard Portfolio

This Power BI portfolio presents an in-depth analytical solution for **Himalaya Kött & Video**, a mid-sized grocery boutique known for its exceptional goods and outstanding customer service. The project includes multiple dashboards focused on **Sales Performance**, **Employee Overview**, **Campaign Effectiveness**, and **Financial Analysis** via a **Chart of Accounts**.

The dashboards aim to support strategic decisions across operations, marketing, and finance with clear KPIs and visuals.

---

## Project Overview

**Company Profile**  
*Himalaya Kött & Video* is a local boutique that offers a wide variety of high-quality food and lifestyle products. The brand has earned community loyalty due to its quality offerings and personalized customer experience.

**Goal**  
To build a data-driven business dashboard solution that supports operational and strategic decisions, with the following focus areas:

- Product-level sales analysis  
- Campaign performance and net revenue tracking  
- Employee structure and demographics  
- Financial performance (monthly income, costs, margins)

---

## What I Did

This project involved the full BI lifecycle using Power BI:

1. **Data Extraction**  
   - Pulled data from multiple business systems and exports  
   - Converted and cleaned raw data into structured CSVs

2. **Data Transformation**  
   - Used Power Query to clean nulls, reshape tables, and unify time dimensions  
   - Created custom calculated columns for sales margins, campaign ROI, and monthly KPIs

3. **Data Modeling**  
   - Designed a Star Schema in Power BI:
     - Fact tables for Sales, Campaigns, Finance
     - Dimension tables for Products, Time, Employees
   - Established correct relationships and hierarchies for drill-down analysis

4. **Visualization & Reporting**  
   - Built intuitive dashboards with rich interactivity
   - Used slicers, matrix views, tree maps, bar charts, pie charts, and KPI cards  
   - Organized navigation between report pages for seamless experience

---

## Dashboards Breakdown

### 1. Portfolio Overview

- Project introduction and purpose  
- Company profile summary  
- Navigation to key dashboards  
- Mini KPIs for active employees and top campaigns  

**Screenshot:**  
![Portfolio Overview](https://github.com/fuzzyzester/HKV_BusinessIntelligence_solution/blob/main/powerbi_hkv_mainpage%20(1).png)

---

### 2. Sales Dashboard

- Overall sales KPIs (Total Sales, Purchase Price, Sales Margin, Margin %)  
- Top 5 and bottom 5 product categories by performance  
- Sales Overtime visualized across months, quarters, and year  
- Drillable table for category-level revenue and cost comparison  

**Screenshot:**  
![Sales Dashboard](https://github.com/fuzzyzester/HKV_BusinessIntelligence_solution/blob/main/powerbi_hkv_salespage%20(1).png)

---

### 3. Employee Dashboard (Preview on Main Page)

- Gender distribution (Man, Woman, Non-binary)  
- Total number of active employees  
- Integrated into the Portfolio front page  

**Screenshot included in:**  
![Portfolio Overview](https://github.com/fuzzyzester/HKV_BusinessIntelligence_solution/blob/main/HVK_hrDashboard.png)

---

### 4. Product Campaigns

- Top 5 campaigns by net revenue  
- Visual breakdown of campaign codes and size  
- Campaign performance compared to non-campaign items  
- Net margin impact and revenue lift during active weeks

**Screenshot included in:**  
![Portfolio Overview](https://github.com/fuzzyzester/HKV_BusinessIntelligence_solution/blob/main/hvk_SalesCampaign.png)

---

### 5. Chart of Accounts (Financial Dashboard)

- Monthly income and direct cost tracking  
- Calculation of TB1, TB2, Result, and Result %  
- Visual layout of fixed and variable costs like rent, water, cleaning, etc.  
- Time slicer for financial year/month selection  

**Screenshot:**  
![Chart of Accounts](https://github.com/fuzzyzester/HKV_BusinessIntelligence_solution/blob/main/powerbi_hkv_coa1856%20(1).png)

---

## Tools Used

- Power BI Desktop  
- DAX (for custom KPIs like sales margin %, result %)  
- Power Query (ETL operations)  
- CSV (intermediate data structure)  
- Star Schema modeling  
- Interactive dashboard design (UX)

---

## Key Highlights

- All-in-one interactive solution combining operational, HR, and financial views  
- Clear visual layout and user-friendly filters (date, campaign, category)  
- Real-world KPIs: Net Revenue, Sales Margin, Result %, Active Employee Count  
- Efficient model design with reusability and scalability in mind

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop  
2. Use the navigation buttons (HOME, SALES, etc.) to explore each section  
3. Use slicers to filter by product, month, campaign, or department  
4. Review charts and tables for detailed insights  

 
