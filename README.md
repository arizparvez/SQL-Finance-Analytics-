# Problem Statement:
Delivered an automated, easy-to-interpret monthly sales report that provided Croma-focused product-level insights. This enabled stakeholders to track revenue, assess product trends, and support data-driven decisions for inventory and sales planning.
***
***AtliQ Hardware SQL Project: A Step-by-Step Execution Plan:***
-  Created User-Defined Function get_fiscal_year(date) : Returns fiscal year based on the input date (April–March format).
-  Created User-Defined Function get_fiscal_quarter(date): Returns fiscal quarter (Q1–Q4) based on input date.
-  Joined Tables:  Used LEFT JOIN to combine fact_sales_monthly, dim_product, and fact_gross_price.
-  Generated Report for Customer 90002002:  Included fields - month, product, variant, sold quantity, gross price per item, and gross price total.
-  Created Stored Procedure get_monthly_gross_sales_for_customer(customer_code): Accepts a customer code, outputs sales report (max 1 million rows), ordered by month (descending).
-  Calculated Gross Price Total – As product of sold quantity × gross price per item.

**Result**
The report identified top-performing product variants driving Q4 FY2021 revenue, highlighted pricing inefficiencies in low-selling items, and provided actionable insights to optimize promotions and inventory planning.

