# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Data and Kaggle Challenge

## Problem Statement
This project aims to identify areas contributing to high transacted prices and where the highest transacted volume occurs, using a data science approach, so as to help realtors of Skywalker Property Advisors gain a competitive advantage in the Ames Housing Market.

## Background
The city of Ames is one of cities in Iowa State, US. 

In Ames, the situation of property market housing is stable, with the number of houses sold per year from year 2006-2010 keep relatively stable at ~400+, even though US is experiencing Subprime financial crisis due that period. 

There are plenty of Property Advisors in Ames, and Skywalker Property Advisors is one of them. 

As data scientist to advise the realtors of Skywalker Property Advisors in the year 2010, data of houses sold in Ames in 2006-2010 (until July) have being extensively analysed on and various observations are obtained. With these observations, recommendations were made to the Realtors to help them to improve their sales, and to gain a competitive advantage in Ames Housing Market.

## Data Dictionary
Data Dictionary for all datasets are being stored in this link below:

[Data Dictionary](http://localhost:8888/notebooks/OneDrive/Desktop/DSI23%20-%20Project%202/Codes/Appendix%202%20-%20Data%20Dictionary.ipynb)


## Brief Summary of Analysis
Using ridge model, we have obtained the top 10 factors (coefficients) which impact the housing sale price in a positive and negative manner.
The following are the details of the factors:

1) **Neighborhood**

*Data observations:*

2 neighborhoods that have positive impact to saleprice: Northridge Height and Northridge.
3 neighborhoods that have negative impact to saleprice: Edwards, North Ames and Old Town.
Based on salesprice,
-Houses in Northridge Heights and Northridge have mean sale price of >$300,000, yielding higher amount of revenue and commission.
-Houses in North Ames, Edwards, and Old Town have mean sale price of <$150,000, yielding lesser amount of revenue and commission.

*Recommendation:*

Realtors could focus more on marketing the houses in Northridge Heights and Northridge to generate higher revenue through higher sale prices.

2. **Quality of House**

*Data observations:*

The Overall, External, and Kitchen Qualities of the house all have a positive impact on sale prices.
The higher the Overall, External, and Kitchen Qualities of the house, the higher the mean sale price of the house.
Current situation: Most number of houses sold -
have 3 - 4 (Average - Good Rating) for external quality and kitchen quality,
and a range of 5 to 8 (Average- Very Good Rating) for overall quality.

*Recommendation:*

For clients with below average housing quality, advice them to refurbish their home.
For clients with average/good housing quality, can try persuading them to improve housing quality even more to differentiate themselves for a higher saleprice.

3. **Fireplaces**

*Data observations:*

The no. of Fireplaces increases SalePrice.
There is a very large jump in sale price from 0 to 1 fireplace.
This is because fireplace is important to residents in Ames during the cold winter period.

*Recommendation:*

To advise clients to build at least a fireplace for their house before wanting to sell them to increase saleprice.

4. **Square Footage of House**

*Data observations:*

The square footage of houses (1st floor, 2nd floor, & garage area) all positively impacting the saleprice.
Houses with a 1st Floor approx 800 - 1200 sqft have been the most commonly sold, with houses 800 - 900 sqft being the standout performer.
Houses with a 2nd Floor that measures 700 - 900 sqft have been the most commonly sold.
Houses with garage area of 300 sqft, and a range of 450 - 600 sqft have been the most commonly sold.

**Factors negatively impact house saleprice**

1. **Exterior 2nd HdBoard:**
-   Poor moisture resisting properties   
-   Requires periodic inspection and maintenance

2. **Exterior 1st Stucco:**
-   Wooden frame underneath
-   Does not do well in wet climates (eg. high snowfall)

**Factors having negligible impact on house saleprice**
1. **Lot shape**
2. **Fence**

## Conclusions
**Neighborhood**

Focus on marketing the houses in Northridge Heights and Northridge.

**Quality of House**

Advice clients with below average housing quality to refurbish their home.

**Fireplaces**

Focus on marketing houses with at least 1 fireplace and encourage clients to build a fireplace if they do not have one.

**Housing Exteriors**

 Avoid houses with hardboard or stucco exteriors as they are prone to rot and mold especially with the above average snowfall in Ames.

**BIGGER is NOT always BETTER**

A bigger house may have a higher potential sale price, but that also means that it could have a lower chance of being sold due to a lower number of potential buyers who can afford it.

## Future Work
**Total No. of Houses in Neighborhoods**

This would allow us to evaluate the percentage % of houses that are sold across all neighborhoods.

**Demographic of Neighborhood and Buyers**

Age range, Marital Status, Family size, No. of kids could play a part in helping realtors recommend the right houses to the right buyers.

**Sale price in real value to take into account of inflation**

Rate of inflation would allow us to “reflect” the past sale prices based on today’s economy.
