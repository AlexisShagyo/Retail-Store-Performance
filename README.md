# 🕵️‍♀️Project Overview

The CEO and CMO have requested to provide insights on the sales performance of the retail store to assess their plans on expansion aside from the main branch in United Kingdom. 

## ***Business Questions***

- The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

- The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

- The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

- The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.
<br>

## Methods

Before the beginning of the analysis, a variety of checks were conducted for quality control and reliability of the datasets. Utilizing Excel and Power Query, here are the steps that were taken:
1. Removing duplicate values from the dataset
2. Ensuring the unit price and number of units sold are not zero
3. Checking that unit price and numbeer of units sold has no negative value
4. Deleting nulls or blanks
5. Removing records that has no specified countries in it
6. Adding a new column entitled 'Sales' that multiplies unit price to number of units sold
<br>

## 📊 Visualization
<img src="https://github.com/AlexisShagyo/Images/blob/main/Retail%20Store%20Perfomance.jpg" alt="Image" width="800" height="450">
<br>

## 📑 Insights
<img src="https://github.com/AlexisShagyo/Images/blob/main/Top%20Sales.jpg" alt="Image" width="800" height="200">

- Data indicates that certain months of the year, particularly September, October, and November, experience exceptional growth. However, the decline observed in December remains unexplained, as the data for that month is still incomplete. This suggests that the retail business exhibits seasonality in sales, especially in the final months of the year.

- In addition to our main branch in the United Kingdom, which achieved an impressive $7.8 million in sales, we see remarkable potential for growth in the Netherlands, Ireland, and Germany. There is significant potential to expand our operations in these countries, particularly considering the substantial revenue difference—the Netherlands, for example, has sales of $286,000. Expanding our branches in these locations could lead to increased sales opportunities.

- The highest revenue-generating customer purchased only 17% more than the second-highest, which shows that the business does not rely solely on a few customers for its revenue. This suggests that the bargaining power of customers is low, placing the business in a strong position.

- Finally, the map chart shows that apart from the UK, countries such as Netherlands, Ireland, Germany, France, and Australia are generating high revenue and the company should invest more in these areas to increase demand for products.
<br>

<img src="https://github.com/AlexisShagyo/Images/blob/main/Lowest%20Sales.jpg" alt="Image" width="800" height="200">

- As for the expansion plans, it is recommended to look at the top 5 lowest performing countries in terms of sales. As the idea of expansion can take a lot of money, time, and effort, we could look into countries like South Africa, Czech Republic, Bahrain, and Saudi Arabia and investigate the factors why our products are not selling well in these markets. We may need to look at our marketing efforts as well, if we are spending  a large amount of money and not getting the target returns, we might as well consider halting or stopping our operations.
<br>

***_☑️ With that being said, there is another business questions that needs to be assessed such as_***
1. What specific factors are contributing to the low sales performance in the identified countries?
2. How are the current marketing efforts being assessed in terms of effectiveness?
3. What alternative strategies could be considered if halting operations in these markets is deemed necessary?  

