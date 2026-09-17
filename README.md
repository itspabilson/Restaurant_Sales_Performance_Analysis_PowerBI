# Restaurant Sales & Operations Analysis (SQL & Power BI)
# Public Restaurant Sales Dataset sourced from Kaggle (containing transactional records across multiple products and channels).

## Project Overview
This end-to-end data analysis project focuses on analyzing restaurant sales performance, customer purchase behaviors, and channel distribution. The workflow spans from managing and querying operational data in **SQL Server** to building an interactive analytics dashboard in **Power BI**. 

---
##  Tech Stack & Tools
* **Database Management:** SQL Server (SSMS)
* **Data Visualization & Analytics:** Power BI Desktop
* **Data Query Language:** T-SQL
* **Data Modeling & Calculations:** DAX (Data Analysis Expressions)

---
##  Key Metrics & DAX Measures

* **Total Revenue**
  ```dax
  Total Revenue = SUM('9 Sales-Data-Analysis'[Price])
  Total Orders = DISTINCTCOUNT('9 Sales-Data-Analysis'[Order ID])
  AOV = [Total Revenue]/DISTINCTCOUNT('9  Sales-Data-Analysis'[Order ID])
