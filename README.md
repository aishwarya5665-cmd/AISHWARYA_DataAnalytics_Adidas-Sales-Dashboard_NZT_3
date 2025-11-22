**ADIDAS SALES ANALYSIS DASHBOARD-POWERBI DASHBOARD**-This project represents a structured and interactive dashboard which is built using ADIDAS SALES DATA.It describes about the complete 
Data Analytics workflow by Data Importing,Cleaning,Modelling,DAX Calculations and sales dashboard.

**PROJECT OVERVIEW**-Analyse Adidas sales performance across regions, customers, products, and time.Provide insights for decision-making in sales, marketing, and inventory.
Interactive dashboard built using Power BI.

**DATASET SUMMARY**-The dataset contains 5 related tables-ADIDAS SALES,CUSTOMER,PRODUCT,SUPLLIER AND WARRANTY DATA.

**DATASET PREPARATION**-**Imported Excel files into Power BI
Removed duplicates & null values
Standardised column names
Corrected data types (text, number, date)
Cleaned numeric formatting (e.g., currency symbols).
DATA MODELLING-Star Schema

**Key DAX Measures**

Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Profit Margin (%) = DIVIDE([Total Profit], [Total Sales]) * 100
Total Orders = DISTINCTCOUNT(Sales[OrderID])
Average Order Value = DIVIDE([Total Sales], [Total Orders])
Total Quantity = SUM(Sales[Quantity])

**Dashboard Features**

KPI Cards: Total Sales, Profit, Orders, Margin
Charts:Bar chart – Sales by Region,Donut chart – Profit by Category,Line chart – Monthly Sales Trend,Bar chart – Sales by Sales Method,Tables: Top 10 customers,
Slicers: Region, Category, Sales Method, Date

**INSIGHTS**-Total Sales: 159K,Total Profit: 22.94 K,Profit Margin: 14.39%,Total Orders-19,Best-performing regions: South, West, Northeast,Top channels: Online & Outlet
Strong monthly peaks indicating seasonal demand,Top customers contribute significantly (>19k each)

**TOOLS USED**
Microsoft Excel
Power BI Desktop
Power Query
DAX



Optional: Map (Sales by Region)

