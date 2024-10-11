# Consumer-Goods-Analytics---Ad-Hoc-Insights-MySQL-Power-BI-

Project Overview and Problem Statement
Atliq Hardware (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too. specializes in selling computers and accessories.

The management noticed that they did not get enough insights to make quick and smart data-informed decisions. However, Tony Sharma (Data Analytics Director ) wants to expand their data analytics team by adding several junior data analysts. So he decided to conduct a SQL challenge which will help him understand both tech and soft skills

Now the company wants insights for 10 ad hoc / business requests.

This project is part of the data analytics boot camp at codebasics.

**__Data Structure/ Data Modeling and Tools__**

The 'gdb023' (atliq_hardware_db) database was provided to me to work on and it includes six main tables:

dim_customer: contains customer-related data
dim_product: contains product-related data
fact_gross_price: contains gross price information for each product
fact_manufacturing_cost: contains the cost incurred in the production of each product
fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
fact_sales_monthly: contains monthly sales data for each product.
Here is the Data Model that I have created in Power BI for the Visualization part -



![image](https://github.com/user-attachments/assets/0ccc3390-e126-41c8-a6fe-380570c88b70)


Tools used -

I used My SQL to answer the questions
and Power BI for visualization.

10 Ad-Hoc Requests and Answers:
1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region.

   
![image](https://github.com/user-attachments/assets/0c99f060-79ea-45f8-8c66-e8d0878ae0ff)


3. What is the percentage of unique product increase in 2021 vs. 2020? The final output contains these fields, unique_products_2020, unique_products_2021, percentage_chg



![image](https://github.com/user-attachments/assets/795d710f-1a13-4d57-8837-eab5414c96e2)

4. Provide a report with all the unique product counts for each segment and sort them in descending order of product counts. The final output contains 2 fields, segment product_count.


![image](https://github.com/user-attachments/assets/ee633e6b-915e-4542-bfb6-81e8be22fc2f)



5. Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? The final output contains these fields, segment product_count_2020, product_count_2021, difference.


![image](https://github.com/user-attachments/assets/ca4e6444-6af9-4b5a-b2b4-f2e9d70a8cc8)



5. Get the products that have the highest and lowest manufacturing costs. The final output should contain these fields, product_code, product, manufacturing_cost.


   

![image](https://github.com/user-attachments/assets/ecb80da8-5307-4f9e-9b37-3ca9934b3238)


6. Generate a report that contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market. The final output contains these fields, customer_code, customer, average_discount_percentage.




![image](https://github.com/user-attachments/assets/682a6678-780f-4f52-ad22-eb42cf0e3664)




7. Get the complete report of the Gross sales amount for the customer “Atliq Exclusive” for each month. This analysis helps to get an idea of low and high-performing months and make strategic decisions. The final report contains these columns: Month, Year, and Gross sales Amount.

   

![image](https://github.com/user-attachments/assets/e5c35f3e-a191-46b3-b260-b2302cffc2f6)



8. In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity, --> Quarter, total_sold_quantity



![image](https://github.com/user-attachments/assets/2466d37a-88ac-4363-962f-e373399ed58b)



9. Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? The final output contains these fields --> channel, gross_sales_mln, percentage.





![image](https://github.com/user-attachments/assets/a77d45af-ed28-48d6-aef9-1079a042a1dc)



10. Get the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? The final output contains these fields, division, product_code.



![image](https://github.com/user-attachments/assets/ad424230-c462-4cd5-ab24-a9b9544d0558)

==============================================================================================================================================================================
===============================================================================================




NOTE-

Atliq hardware ad-hoc insights presentation pdf - In this file, you will find the presentation

ad-hoc-requests - In this file, you will find all the Questions

all Ad-hoc SQL Queries - In this file you will find all the Answers











