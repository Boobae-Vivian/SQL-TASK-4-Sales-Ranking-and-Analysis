# SALES RANKING AND ANALYSIS

## INTRODUCTION
In this analytical endeavor, we will embark on a comprehensive exploration of sales data within the West region, aiming to unveil key insights into customer performance and product sales rankings. The primary objective is to identify and determine the top 5 customers in the West region, leveraging the powerful capabilities of window functions. Specifically, we employ the row_number() window function to establish a ranking of customers based on their total sales. Simultaneously, we utilize the rank() and dense_rank() window functions to assign unique numerical identifiers to individual products, emphasizing their sales performance. This task not only facilitates the identification of top-performing customers but also delves into a granular analysis of product sales, enriching our understanding of market dynamics within the West region.

## PROBLEM STATEMENT

 Objective:

Identify the top 5 customers in the West region based on the highest total sales.
Utilize window functions for efficient analysis and ranking.
II. Data Source:

Access a dataset containing sales information, including customer details and product sales, specifically focusing on the West region.
III. Window Functions:
A. Total Sales Ranking:
1. Implement the row_number() window function to rank customers based on their total sales.
2. Extract the top 5 customers with the highest total sales in the West region.

B. Product Sales Ranking:
1. Employ the rank() window function to assign unique numbers to each product based on their sales.
2. Utilize the dense_rank() window function for an alternative ranking approach.
3. Generate separate rankings for products to capture different aspects of their sales performance.

IV. Output:

Provide a comprehensive report highlighting the top 5 customers in the West region and unique rankings for each product based on sales.
V. Significance:

Enhance decision-making processes by identifying key customers and gaining insights into product sales dynamics within the West region.
VI. Scope and Limitations:

The analysis is confined to the West region.
The rankings are based on the available sales data, and additional factors may influence the overall analysis.
VII. Deliverables:

Submit a detailed report outlining the top 5 customers and product rankings, supported by visualizations and insights derived from the window function analysis.

