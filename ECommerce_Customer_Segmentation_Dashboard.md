# E-Commerce Customer Segmentation and Sales Dashboard (Power BI)

##  Project Overview
This Power BI project analyzes UK-based e-commerce sales transactions and customer behavior.  
It combines RFM (Recency, Frequency, Monetary) segmentation with sales insights to identify customer groups such as **Champions, Loyal Customers, and At-Risk Customers**.

---

##  Objectives
- Understand customer purchasing behavior
- Identify high-value and at-risk customer segments using RFM analysis
- Visualize sales trends across time and geography
- Support data-driven marketing and retention strategies

---

##  Data Source
Dataset: *UK-based E-Commerce Transactions (Kaggle)*  
**Columns:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

##  Key Data Transformations (Power Query)
- Removed nulls in CustomerID  
- Extracted Year, Month, Day from InvoiceDate  
- Calculated Total Sales = Quantity × UnitPrice  
- Built RFM metrics: Recency, Frequency, and Monetary  
- Segmented customers into groups (Champions, Loyal, At-Risk, Lost)

---

##  Dashboard Features
- **KPI Cards:** Total Sales, Unique Customers, Total Quantity, Average Order Value  
- **Charts:**  
  - Sales by Month (Line Chart)  
  - Sales by Product Description (Bar Chart)  
  - Sales by Country (Map Visual)  
  - Customer Segmentation Overview (Column Chart)  
- **Table:** Average Recency, Frequency, and Monetary by Segment  

---

##  Business Insights
- Champions and Loyal customers drive most of the sales volume.
- A large portion of customers are inactive ("Lost" or "Needs Attention") — potential for reactivation campaigns.
- Product sales have strong seasonality trends across months.
- High-value customers show shorter recency cycles and larger order sizes.

---

## Reccomendation
- Re-engage “At Risk” and “Lost” customers with targeted discounts or loyalty programs.

- Focus marketing on Champions and Loyal customers for retention.

##  Tools Used
- Power BI  
- Power Query  
- DAX  
- Microsoft Excel (Data Exploration)

---

##  Author
**Synthia Atieno Oduor**  
 *Junior Data Analyst | Excel | SQL | Power BI*  
 Kenya  


