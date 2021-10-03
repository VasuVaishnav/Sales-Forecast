# Sales Forecasting
## Overview:
* All the DataSet are downloaded from Kaggle.
* This analysis is done for forecasting on Store Dataset.

## Steps and Logic:
* Whenever dealing with Time Series or any data similar to Store data, i.e. if it contains sales related information along with dates, do include yearly, monthly and weekly sales for deep and proper analysis.
* Feature enginnering is done for the same reasoning.
* Cummulative graphs also helps in understanding where there was a surge growth.  
 ![Image1](https://github.com/VasuVaishnav/Sales-Forecasting/blob/master/image1.png)  
As the figure shows, we can see whether increase is steep or shallow.
* While dealing with Raw data, cleaning of data is an important step. So we can either remove all the null values or we can replace them with corresponding mean/median values.
* Generally if null values are less than 7%, we can ignore and drop them in order to maintain integrity. However, it is always depends on analyst to choose the threshold.
* However, I have used Median as the value for missing values.
* **_Lies, damned lies, and statistics_** , yes it is important to know that _sharp knife is nothing without a sharp eye_ . Stats can mislead. For example:  
![Image2](https://github.com/VasuVaishnav/Sales-Forecasting/blob/master/image2.png)  
![Image3](https://github.com/VasuVaishnav/Sales-Forecasting/blob/master/image3.png)  

* As second image shows that Store B is the best and Store D is worst but actually in terms of more profit it is not True. So Have to be aware of such instances

## Conclusions
* The most selling and crowded StoreType is A.
* The best "Sale per Customer" StoreType D indicates to the higher Buyer Cart. To benefit from this fact, it can be considered that proposing bigger variety of its products.
* Low SalePerCustomer amount for StoreType B indicates to the possible fact that people shop there essentially for "small" things. Eventhough this StoreType generated the least amount of sales and customers over the whole period, it shows a great potential.
* Customers tends to buy more on Modays when there's one promotion (Promo) and on Sundays when there's no promotion at all (both Promo and Promo1 are equal to 0).
* Promo2 alone doesn't seem to be correlated to any significant change in the Sales amount.
* Weekends and Monday are the most productive time for Sales.
* Promo and Holiday are directly proportional.
* More Sales are observed in late November and full December due to Holiday Seasons.
