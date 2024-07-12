# Banana-Sales-Analysis

### PROJECT OVERVIEW

This data analysis project aims to provide insights into the sales performance of a subscription based Software as a Service (SaaS) company over the past years. By analyzing various aspects of the data, we seek to identify trends and pick out useful information to make data driven recommendations about upselling of non-paying customers, forecast the future sales of the company and gain a deeper understanding of the company's performance and how improvement in its performance can drive the sales of the company further.

### Data Sources

Data : the primary data used for this analysis is the "Banana_Sales_Data.csv" containing detailed information about the sales of the company over the years, how the data was cleaned,prepared and analysed for insights to answer the main questions surrounding upselling of non-paying customers and also further analysed to gain more useful insights that can help the company's performance.

### Tools

- Microsoft Excel
   - Data cleaning| Data Preparation| Data Analysis| Data Visualization| Trends| Forecasting

### Dsta Cleaning/Preparation

The following tasks were performed
- Data loading and inspection
- Handling missing data
- Data Cleaning and formatting
   - Reducing the columns to only those required for analysis
   - Adding new calculated field columns derived from the data present

### Exploratory Data Analysis (EDA)

EDA involved exploring the Banana sales data to answer questions that help in understanding the data, find trends and correlation and also generate hypothesis for further analysis. The following was observed:
1. Banana has sold over 35,101 subscriptions for $693,025, with an average customer bringing in $312 each month.
2. It is observed that there are some non-paying users since the number of users does not tally with the number of licences bought, an average of $20 is the sales per subscribers(this was derived by using the number of licenses bought) which is broken down by the subscriber type into $0 for basic, $10 for Premium, $25 for business and $27 for enterprise

### Data Analytics

1. With the existence of non-paying customers,the senior management is looking to identify upsell opportunities. Upsell means getting non-paying accounts to convert to paying accounts. In this dataset, the Subscription Type has four tiers. From worst to best, they are Basic, Premium, Business, and Enterprise. Based on futher analysis of the data, it's incredible that throughout the entire sales history, Bananas could have made over $272,000 had all their customers been paying. This is a big opportunity for them to make more money from existing customers even though  we can't go back in the past to collect this money.

2. This begs for the question about which accounts should be targeted for upsell opportunities. The Upsell of the last month( Current Upsell, a total amount that could be earned if Bananas got every active non-paying user to upgrade their account.

) was determined for each group and grouped based on priority of upsell opportunities into: High - >= 400,Medium - >=100, Low - <100

3. Some trends were also observed in the sales trend wookbook, over the past months of the sales history from 07/01/2020-01/06/2021. There is an increase in the number of customers, an increase in the total sales but a reduction in the average sales and the ratio of non-paying to paying customers( this is as a result of increase in the number of customers converting to paying subscription and reduvtion in the enterprise sales share compared to that of business and premium which are increasing over the months).

4. Though the current upsell is insightful, it is unrealistic as Bananas cannot get 100% of customers to upgrade and they aim to achieve a target sales of $100000 next month? We can play around with the numbers with scenario analysis to see how much we think this is a more realistic sales opportunity. The following was observed:

  - To get a target of 100000 or above next month as requested by the senior management, the conversion rates(the rate at which non-paying customers upgrade their subscriptions) can be manipulated or the licence price canbe manipulated given that the licence bought remains stable or higher.
    - Demand could go down with increase in the price, this calls for more forecast. Goal Seeker, Scenerio Manager and Data table were used to ask and answer what-if questions regarding the changes in price against the changes in demand.
5. The leadership team at Bananas is goal planning for next month, and they're curious about what sales might be. They want us to forecast this for them using historical data. Four  different forecasting methodologies were used here so as the compare the accuracy of the forecast devired
 - simple moving average (SMA)and weighted moving average (WMA) forecasted a sales of 70538	and 73491 respectively for the next month.
 - Banana's sales data seems to have an exponential trend. This means banana sales is rapidly growing.this is s only a graphic representation but we need actual numbers that can be reporeted on
 - Bananas would like actual numbers for a forecast that uses a sophisticated methodology and can consider seasonality and confidence levels, Forecast Sheet tool was used to create a sophisticated prediction model in seconds!Nice work! The choice between a higher or lower confidence interval depends on the specific goals, risk tolerance, and the nature of the decision you're making based on the forecast.

As you saw, there is a tradeoff between the confidence level and the precision of the forecast, it depends on if the analyst prefers precision over confidence, and the risk associated with the forecast being incorrect should be taken into account.





### Recommendation
1. Next month, the sales team would need a 24% growth rate to hit $100,000 in revenue. This canbe achieved by increasing the subscription prices of the upsell oppurtunity given that the number of subscrition upgrade does not reduce more than 5% premium,3% for business and 2% for enterprise subscriptions at prices of $15,
$35 and $33 each respectively.( Further results of the relationship between manipulation of prices against the % drop in demand canbe checked in the scenerio analysis workbook).Of course, scenarios are not real world data, so while they can help drive strategy, they must be tested against the real world.
2. 
3. 
.
4. 

