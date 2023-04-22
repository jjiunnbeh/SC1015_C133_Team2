# SC1015 Mini Project : Predicting the price of diamond

## Predicitng Price of Diamond prices for general public looking to buy diamonds ## 
In general, people have limited knowledge about the prices of diamonds and diamond sellers capitalize on this by selling diamonds with unfair prices. 
So , we are going to try to predict the prices of diamonds based on the 4Cs(colour, clarity , cut , carat) , so that people can have a better understanding on
the prices of diamonds and check if they are being sold to them at a fair price.


## The available features are: ##

 price : USD price

 carat : weight of the diamond --> 1 carat equals 0.2 grams

 cut  : quality of the cut (Fair, Good, Very Good, Premium, Ideal)

 color  : diamond colour, from J (worst) to D (best)

clarity  : measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

 depth : measure of the depth in relation to the width of the diamond’s table, calculated as --> Depth (%) = Depth (mm) / Diameter (mm)

 table  : top facet of the stone; table percentage is the ratio between the table size and the diameter of the diamond

 x  : length in mm

 y  : width in mm

 z  : depth in mm
 
## Models Used ##
1. Linear Regression
2. Random Forest Regression (3 versions) with hyperparameter tuning
3. XGBoost Regressions (3 versions) with hyperparameter tuning

## Conclusion ##
In conclusion, we have faced different limitations thorughout the preparation of this project. The large dataset used in this project is difficult to observe in detail. Hence, with the proper use of different graphs and plots, the details can be clearly understood such as the spread of data, trend of data and relationship between the variables. Beside, the dataset contains a lot of categorical data, which limits the implementation of regression in the training process. By implementing label encoding, the categorical data is converted to numerical data, which can be used in the regression model as well. 

For the future improvement, exploration of more hyperparameters in the regression model is importatnt to further optimize the training model performance. More predictors such as the dimension of diamond should be included in the training process if the information about the predictors are more readily accessible to the customer in the future.

## What did we learn? ##
## Contributors ##
| Name              |                    Contributions                     |
|---|:---:|
| Beh Jia Jiunn |  contributions|      
|  Tan Wu Ji |   contributions |
| name |  contributions|
## References ##
