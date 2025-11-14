# **Business Insights 360 – Power BI Project**

## **📌 Project Overview**

AtliQ Hardware is a rapidly growing global company that has adopted **Power BI** for the first time to improve decision-making across Finance, Sales, Marketing, and Supply Chain.  
This project supports stakeholders with complete, centralized, data-driven insights.

I completed this project by following the Codebasics Power BI Course.  
 
👉 **Live Report Link:** https://app.powerbi.com/view?r=eyJrIjoiNjg1NzIyZTEtMjNhNi00YmI0LWI2MGEtYmY4M2RiMmQ4NDAzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9


---

## **🛠️ Tech Stack**

- SQL  
- Power BI Desktop  
- Excel  
- DAX  
- DAX Studio  
- Project Charter  

---

## **📚 Power BI Techniques Learned**

- Asking stakeholder questions before development  
- Creating DAX measures & calculated columns  
- Data modeling (Snowflake schema)  
- Bookmarks for toggling visuals  
- Page navigation with buttons  
- DIVIDE() to avoid zero-division errors  
- Creating Date Table using M-language  
- Dynamic titles based on filters  
- KPI indicators & conditional formatting  
- Data validation  
- Publishing to Power BI Service  
- Auto-refresh setup using Personal Gateway  
- Power BI App creation  
- Workspace collaboration & access permissions  
  

---

## **📘 Business Terms Used**

- Gross Price  
- Pre-Invoice Deductions  
- Post-Invoice Deductions  
- Net Invoice Sales  
- Gross Margin  
- Net Sales  
- Net Profit  
- COGS (Cost of Goods Sold)  
- YTD (Year to Date)  
- YTG (Year to Go)  
- Retailer / Direct / Distributor  

---

## **🏢 Company Background**

AtliQ Hardware sells computers and accessories worldwide through Retailers, Direct channels, and Distributors.  
The company experienced losses due to intuition-based expansion decisions, especially in the US market.  
To compete with data-driven competitors, they adopted analytics and implemented the **Business Insights 360** dashboard.

---

## **📝 Questions Asked Before Starting the Project**

- What is the primary objective of the dashboard?  
- How will success be measured?  
- What is the project timeline?  
- Do stakeholders require a preview version?  
- What expectations or concerns do stakeholders have?  
- Who will use this dashboard?  
- What data sources are needed?  
- What risks could occur?  
- Any design requirements from stakeholders?

---

## **🗂️ Dataset Understanding**

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions  

- gdb041:
    - dim_customer
        - **27** distinct markets (ex India, USA, spain)
        - **75** distinct customers thorough out the market
        - **2** types of platforms
            - Brick & Motors - Physical/offline store
            - E-commerce - Online Store (Amazon, flipkart)
        - Three channels
            - Retailer
            - Direct
            - Distributors
    - dim_market
        - **27** distinct markets (ex India, USA, spain)
        - 7 sub-zones
        - 4 regions
            - APAC
            - EU
            - nan
            - LATAM
    - dim_product
        - Divisions
            - P & A
                - Peripherals
                - Accessories
            - PC
                - Notebook
                - Desktop
            - N & S
                - Networking
                - Storage
        - There are 14 different categories, Like Internal HDD, keyboard
        - There are different variants available for the same product
    - fact_forecast_monthly
        - This table is used to forecast the customer’s need in advance, which can help in
            - Higher customer satisfaction
            - Reduced cost in warehouses for storage purpose
        - The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
        - All the date of the month will be replaced by the start date of the month
        - It will have all the column names and in the end it will have the forecast quantity need of the customer
    - fact_sales_monthly
        - This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.
- gdb056
    - freight_cost
        - This table has details of travel cost and other cost for each market with fiscal year
    - gross_price
        - Has the details of gross prices with product code
    - manufacturing_cost
        - Has the details of manufacturing cost with product code with year
    - Pre_invoice_dedutions
        - Has the details of pre invoice deductions percentage for each cutomer with year
    - Post_invoice_deductions
        - Post invoice deductions and other deductions details


---

## **📥 Importing Data into Power BI**

Datasets were imported from **MySQL** using database credentials.

---

## **🧩 Data Model**

Snowflake schema used for optimal performance.

![Data Model](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Data%20Model.png)

---

## **🎨 Dashboard Design**

The dashboard contains multiple detailed views based on stakeholder requirements.

### ✔ **Home Page**  
### ✔ **Finance View**  
### ✔ **Sales View**  
### ✔ **Marketing View**  
### ✔ **Supply Chain View**  
### ✔ **Executive View**  

---

## **📊 Dashboard Screenshots**

### **Overall View**
![Overall]()

### **Home Page**
![Home](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Home%20Page.png)

### **Finance View**
![Finance](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Finance%20View.png)

### **Sales View**
![Sales](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Sales%20View.png)

### **Marketing View**
![Marketing](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Marketing%20View.png)

### **Supply Chain View**
![Supply Chain](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/SupplyChain%20View.png)

### **Executive View**
![Executive](https://github.com/aarthi-dataanalyst/Business_Insights_360_PowerBI/blob/main/Finance%20View.png)


---

## **🏆 Project Outcome**

This dashboard allows AtliQ Hardware to make fast, accurate, data-driven decisions.  
Stakeholders can analyze KPIs, identify issues, and answer “why” questions with clarity.

---


