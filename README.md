# SQL-Finance-Analytics
1)  Generated a report for customer croma with customer code as 90002002.
2) Report include fields as month, product, variant, sold quantity, gross price per item, gross price total of individual product sales.
3) Join 3 table namely fact_sales_monthly, dim product, fact_gross_price by using the left join.
4) Create a user define function namely get_fiscal_year which taking input as calendar date and giving output as fiscal year.
5) Create a user define function namely get_fiscal_quarter which taking input as calendar date and giving output as fiscal quarter.
6) Used order by clause to get date in descending order and limit the data set to 1 million rows.
7) Create store procedure namely get_monthly_gross_sales_for_customer which taking customer code as input and giving output as gross price total which is the product of sold quantity and gross price.
