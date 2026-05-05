# Customer-Data-Analysis
Customer shopping behavior analysis project with KPI dashboards, trend analysis, and strategic recommendations for business growth.
🛍️ Customer Shopping Analysis (2021–2023):
Project ID: PTID-CDA-APR-26-11978
Course/Module: PRDA–04 Customer Data Analysis
Prepared by: Debaditya Singha Roy
Dataset: Istanbul Shopping Malls (10 malls, 2021–2023)



📌Project Overview:This project performs end-to-end customer shopping behaviour analysis using transaction data from 10 major shopping malls in Istanbul covering the years 2021 to 2023. The goal is to uncover insights about customer demographics, product preferences, and revenue patterns to support data-driven business decisions.

 📁 Project Files:
 customer.ipynb:------ >>>  Jupyter Notebook — data extraction, cleaning, feature engineering, and analysis
 customer_analysis.xlsx  ------->>>>>Processed and enriched dataset used for analysis
 Customer_Dashboard_project.pbix----->>>>>>Power BI dashboard for interactive data visualization
 customer_shopping_analysis_presentation.pptx----->>>>>>Final presentation with insights and recommendations

📊Dataset Description:-----Data collected from 10 shopping malls in Istanbul across 2021–2023.
invoice_no---->>>>Unique invoice identifier
customer_id---->>>Unique customer identifier
gender------>>>>>Customer gender (Male / Female)
age----->>>>Customer age
category---->>>>Product category (Clothing, Shoes, Technology, etc.)
quantity----->>>>Number of items purchased
price---->>>Unit price
payment_method----->>>>Cash / Credit Card / Debit Card
invoice_date--->>>>Date of transaction
shopping_mall----->>>Name of the shopping mall
revenue----->>>>Computed as price × quantity
age_group----->>>>Derived age segment (Teen, Young Adult, Adult, Middle Age, Senior)

Age Group Segmentation:-

term----->>>>>>Age Group---->>>Age Range
Teen ---->>>0–18--->>>
Young Adult---->>>18–25
Adult-->>>>25–35
Middle Age--->>>35–50
Senior---->>>>>>50–100

🔍 Key KPIs Analysed:
1.Total Revenue
2.Total Quantity Sold
3.Total Transactions
4.Average Revenue per Transaction
5.Average Quantity per Order

📈 Key Findings:---
Gender Distribution:--->>>
1.Female customers account for the majority of purchases
2.Female customers generate higher total revenue than male customers

Age Group Analysis
1.Senior and Middle Age groups contribute the highest revenue
2.The Teen segment has the lowest purchasing activity

Product Category Analysis
1.Clothing is the top-selling category
2.Shoes and Technology contribute high revenue
3.Books, Toys, and Souvenirs have comparatively lower sales

Payment Method Analysis
1.Cash is the most frequently used payment method
2.Credit Card usage is second highest
3.Debit Card usage is the lowest


💡 Business Recommendations
1.Focus marketing on female customers — they are the primary buyers
2.Expand clothing inventory — the highest revenue-generating category
3.Create targeted promotions for younger customers to grow the Teen and Young Adult segments
4.Encourage digital payments (credit/debit card) to reduce cash handling

🛠️ Tech Stack
Tool------------->>>>Purpose
Python (Pandas)------->>>>>Data extraction, cleaning, and feature engineering
MySQL-------->>>>>>Source database for raw customer data
Jupyter Notebook------>>>>>>>Interactive analysis environment
Microsoft Excel------->>>>>Data storage and supplementary analysis
Power BI-------->>>>>>Interactive dashboard and visualisation
PowerPoint------->>>>>Final presentation of insights

📄 License
This project was created for educational purposes as part of the PRDA–04 Data Analysis module.
