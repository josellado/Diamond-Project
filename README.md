# Diamond-Project

![alt text](https://diamondsdirect.com/skin/frontend/jewelers/custom/images/diamond_chart.png)

The goal of these project is to predict the price of diamonds based on a series of characteristics. 


Characteristics: 
 
- id: only for test & sample submission files, id for prediction sample identification
- price: price in USD
- carat: weight of the diamond
- cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- color: diamond colour, from J (worst) to D (best)
- clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- x: length in mm
- y: width in mm
- z: depth in mm
- depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
-table: width of top of diamond relative to widest point (43--95)


> STEP 1  
> Clean Data Set (link at describtion)

In these step I clened and transformed the data with the aim ot make my machine learning more precise and accurate 

-  Renamed the columns x,y and z to make them easible to read 
- Used the describe and unique methods to identify any possible outliers 
- Get dummies 

> STEP 2 
> Run different Machine Learning methods 

- I used  7 different methods and found out that the Extra Trees Regressor method worked the best for my data 
- apply different parameters with the aim to lower my RSME as low as possible. ( RMSE: 536.5739)

> STEP 3 

- Run the models with the predict.csv in order to predict the price of diamonds. 

