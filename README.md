INTRODUCTION

In this project, I utilized Microsoft Excel to analyze the sales data of Savill Corporation to gain insights into the sales performance, answer some critical business questions and make necessary recommendations to improve sales performance and revenue generation.

DATASET INFORMATION

The dataset provided is made up of 3 files in Microsoft Excel format containing the company’s sales data for 2021 to 2023. The dataset contains at least 66,000 rows and 15 columns, each giving specific information. The dataset can be downloaded here. Below is the data dictionary:


TOOLS USED:

Microsoft Excel and Power Query were the tools used to clean, Analyze, and visualize this dataset.

DATA TRANSFORMATION

I linked Excel to my folder and used Power Query’s “GET DATA” features to load the data for merging, cleaning, and transformation.


The transformations and cleaning were:

Checking and removing all duplicates in the data.
Identifying null/missing values and extracting values for them by using the FILL functionality of Power Query.

3. Getting the Profit from the Sales and Profit margin using the CUSTOM COLUMN functionality of Power Query.


4. I added a new column, DISCOUNT LEVELS from the Discount column to segment them into levels(0–20% — Low; 21%-40% — Medium; 41% and higher — High) using ADD CONDITIONAL COLUMN functionality of Power Query.


5. Getting the Shipping duration from the Ship and Order Date columns using the CUSTOM COLUMN functionality of Power Query.


6. I identified outliers in the data by using Microsoft Excel’s BOX AND WHISKER functionality. Upon further investigations, I was able to get that they were entered in error and I changed them to the correct values.


7. Other necessary transformation include changing data types. The table was then loaded back into Excel for further analysis. Below is the table after transformation and cleaning.


ANALYSIS

1. Sales and Profitability Analysis

a. Which product categories are the most profitable?

The chart below shows that the Electronics products are the most profitable, with a total profit of over £42m. This can result from a high demand for the products in this category, increasing profitability.


b. How do sales and profits trend over time? Are there seasonal patterns?

The chart below shows a direct relationship between Sales and Profits. As sales increase, profit also increases. A seasonal pattern is observed across each year. The top profit and sales months for 2021 are March and December. For 2022, March and October are the top profit and sales months, and for 2023, August and October are the top profit and sales months.


c. Which cities contribute most to our profits?

The chart below shows that the performance across all the cities are quite good with total profit of over £8m in each City. However, Manchester has a slight higher profit of £8.3m.


d. Which product category has the highest average unit price, and how does this correlate with profitability?

Electronics is the product category with the highest average unit price, as seen in the chart below. The analysis revealed a positive correlation between unit price and profitability as discussed in section (a) above.


e. What is the relationship between discount levels and the quantity sold across various categories?

From my analysis, most products in every category were sold with low discounts. This could be a part of the company’s marketing and promotional strategy to attract more customers.


f. How does the profit margin vary between Corporate and Consumer segments?

Corporate customers contribute about 50.14% of the company’s profit, which is a slight margin compared to the 49.86% of the consumer segment. This small margin could result from the type of products the company sells. The products are essential to both Consumer and Corporate customers.


2. Customer Segmentation Analysis

a. Which segment (Corporate or Consumer) brings in more revenue?

Corporate customers bring in more revenue, with a total of over £102m. This could be a result of the type of products sold.


b. Are there any geographical areas that show significant potential for certain segments?

From my analysis and chart below, Manchester shows significant potential in the Consumer segment, while Birmingham is the city with considerable potential in the Corporate segment. These deductions were made due to the sales generated in both cities for the customer segments.


c. What are the characteristics of our top-spending customers, and how can we better target them?

The top spending customers are characterised by the quantity of goods bought and the specific product category. Highlighted in the table below are the quantity of goods bought by Top-spending customers per Product Categories.


d. Can we identify any patterns in product category preferences across different segments?

From my analysis, I was able to identify that the Customers in both segments have preference for Home Appliances, Books and Toys product categories.


e. How do customer acquisition rates differ across regions, and what might this indicate about our market penetration?

From the chart below, it is evident that there is not much difference in the customer acquisition rate. This could mean that the company has its products evenly spread across the region/cities.


3. Product Performance Analysis

a. Which products have the highest sales volume, and which ones are lagging?

From my analysis, all the products have generated high sales volume. However, the Cookbook has sold the most with 13,481 units. This means that the company is actually using the right marketing strategies across all products.


b. Are there any products that, despite high sales volume, have low profitability?

Products like Fiction novels, T-shirts, Cookbooks, and Toasters, despite having high sales volumes, were not profitable to the company. This could be due to the price at which they are sold.


c. What is the total revenue, total profit and total volume for each product category?

The table below shows the Total Volume of 200,006 units, Total Profit of £57.6m and Total Sales of £204m.


d. Which segment is generating more profit for each product category?

Corporate customers generate the most profit across all the product category. This could be due to their higher purchasing power compared to the Consumer segment of customers.


e. what is the profit distribution across the different segments?

The chart below shows the profit distribution across the segments with Corporate generating over £29m and Consumer generating profit of over £28m.


4. Geographic Market Analysis

a. What regions or cities have the highest sales volume and profitability?

Manchester, Liverpool and Bournemouth are the cities with the highest profitability as highlighted in Green and highlighted in Yellow are Leeds, Sheffield and Liverpool which have the highest sales volume.


b. Are there untapped markets with potential for growth?

From my analysis of the various cities, Leeds appears to have growth potential. The city generates the most sales volume but the lowest profit. This could be due to low margins, overreliance on discounts, and intense competition with competitors.


c. Are there specific products or categories that consistently experience shipping delays? (Average waiting date per product or category).

The Toy, Apparel, and Books categories take an average of 3 days to ship, while Home appliances and Electronics have fewer waiting days. This can be due to delays in logistics operations or improper inventory management.


Dashboard

Using Microsoft excel, I created a dashboard for Savill Corporation using their sales dataset for 2021–2023. The dashboard included a variety of charts, slicers and timeline to visualize the data and communicate the business needs. The dashboard gives an overall summary of the sales performance and Key Performance Indicator (KPIs) of the business. Regularly reviewing the dashboard can help the company identify areas for improvement and make more informed decisions.
