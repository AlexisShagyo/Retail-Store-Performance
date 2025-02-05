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

- For the top performing countries aside from the main branch in United Kingdom, the top 3 performing countries in trms of sales are Netherlands, Ireland and Germany. We can think of expanding our branch on these locations as there is a lot more potential to gain sales considering the big difference of revenue generated in United Kingdom compared to the next top performing countries.

- Data shows that there are some months of the year where exceptional growth is witnessed, particularly on starting from months September, October and November. As for the reason why there is dwntrend when it comes to December, no conclusion can be brought to it as data from that month is still incomplete. This shows that the retail business have seasonality in sales which is on thelast for months of the year.

- The highest revenue generating customer only purchased 17% more than the 2nd highest which shows that the business is not relying only on a few customers to generate the revenue. The bargaining power of customers is low and the business is in a good position.

- Finally, the map chart shows that apart from the UK, countries such as Netherlands, Ireland, Germany, France and Australia are generating high revenue and the company should invest more in these areas to increase demand for products.
<br>

<img src="https://github.com/AlexisShagyo/Images/blob/main/Lowest%20Sales.jpg" alt="Image" width="800" height="200">

- As for the expansion plans, it is recommended to look at the top 5 lowest performing countries in terms of sales. As the idea of expansion can take a lot of money, time, and effort, we could look into countries like South Africa, Czech Republic, Bahrain, and Saudi Arabia and investigate the factors why our products are not selling well in these markets. We may need to look at our marketing efforts as well, if we are spending  a large amount of money and not getting the target returns, we might as well consider halting or stopping our operations.
<br>

***_☑️ With that being said, there is another business questions that needs to be assessed such as_***
1. What specific factors are contributing to the low sales performance in the identified countries?
2. How are the current marketing efforts being assessed in terms of effectiveness?
3. What alternative strategies could be considered if halting operations in these markets is deemed necessary?  

