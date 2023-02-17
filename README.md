# Food Sales Predictions
## An analysis of how certain product & outlet properties affect the sales of different food items

#### Author: Hollyann Stevans

### Business problem:

This analysis focuses on sales predictions for food items sold at various stores. The goal is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.


### Data:

Orginal Source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

#### Data Dictionary:
![Model](https://github.com/hstevans/Food-Sales-Predictions/blob/main/Food%20Sales%20Predictions%20Data%20Dictionary.png)
Source: Coding Dojo Part Time Data Science Program

## Methods
- Data cleaning to prepare the data for accurate analysis - this involved the dropping of unnecessary columns, deciding what to do about missing data, confirming data types are correct for each column
- Creation of exploratory & explanatory visualizations to explain the data analysis in a clear manner 
- Preprocessing to prepare the data for analysis through machine learning to prevent data leakage
- Machine Learning - training models through the creation of a linear regression model and decision tree regressor model, as well as, analyze R^2/RMSE to further explain the data analysis and to explore which model would be best fit for the data

## Results

#### Item Outlet Sales vs. Item MRP
![Model](https://github.com/hstevans/Food-Sales-Predictions/blob/main/Item%20Outlet%20Sales%20vs.%20MRP.png)

> The scatterplot shows a positive correlation between Item Outlet Sales & Item MRP. As Item MRP increases so does Item Outlet Sales.

#### Item Outlet Sales by Outlet Type
![Model](https://github.com/hstevans/Food-Sales-Predictions/blob/main/Item%20Outlet%20Sales%20by%20Outlet%20Type.png)


> The barplot shows that Supermarket Type 3 has the greatest sales, by far of any of the other outlet types, and Grocery store has the least.  Supermarket Type 3 has about $3,600 in sales while Grocery Store has about $400.  

## Model

### Linear Regression Model Evaluation
![Model](https://github.com/hstevans/Food-Sales-Predictions/blob/main/Item%20Outlet%20Sales%20by%20Outlet%20Type.png)

### Decision Tree Regressor Evaluation
![Model](https://github.com/hstevans/Food-Sales-Predictions/blob/main/Item%20Outlet%20Sales%20by%20Outlet%20Type.png)

For this data set, a Linear Regression Model and a Decision Tree Regressor Model were trained/tested.  The Decision Tree Regressor Model is best for analysis of this data. The Decision Tree had a lower RMSE score, indicating that it would not make many bigger mistakes, but instead more smaller mistakes.  The Decision Tree Model still shows high bias though. 





## Recommendations:

The company should focus on the sales performance at each location type (Outlet_Type) and see if stocking items with higher Item_MRP affects sales at locations, like grocery stores, that have low Item_Outlet_Sales.



## Limitations & Next Steps

More exploratory and explantory analysis needs to be done to further support the recommendation.  At the very least, I would like to add further analysis in regards to Outlet_Type, Outlet_Size, and Item_Outlet_Sales.

I would also like to dive deeper into other regression models, as well as, tuning their hyperparameters.


### For further information


For any additional questions, please contact hstevans@gmail.com
