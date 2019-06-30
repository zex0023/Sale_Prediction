# Sale_Prediction

## Dataset:
[Kaggle Competition: Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview)

## Objective:
Given historical sales time-series data from January 2013 to October 2015, including shop name, shop id, item name, item id, item price and item sale amount.
Our task is to use given data to predict November 2015 product sales.

## Motivation:
For many shops and stores, predicting future sales of products can be useful.  They have old sales data and want to know future sales to make decisions of the amount of a certain product to buy and how many of this product to allocate into each store.

Only after knowing the consumers' willingness to buy a certain product can maximize their profit and minimize the loss of over ordering of a certain product.  

In this case, predicting the amount of each product sale in the future can be useful, here we use the sales data of Russian shops to build the model.

## Concerns and possible questions:
1. The dataset is time-series, but should we regard it as a pure time-series question?  We have to build a model for all product sales, however, some product sales amounts are seasonal(just like watermelon are best sellers during Summer) and some are not(maybe Xbox console?).

2. There is a price column, we might not use it, but will it affect the final prediction?  The price increase and price drop can affect sales amount effectively.  So, do we need to predict the price of each product in November 2015 first and take it into account?  

3. Shop details and item details are given, should we use them?  Are there any useful features in it?

4. We will post more questions here if we find any.
