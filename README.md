# Weekend-Project_KNN
### Group members:
- Shaima Alharbi 
- Ebtisam Alrehili 
- Aljowhara Alblaihed
---
### In this project we work on  [Saudi Airbnb Price Prediction](https://github.com/gumdropsteve/intro_to_machine_learning/blob/main/day_10/data/jeddah.parquet).
[Data Dictionary ](https://github.com/gumdropsteve/intro_to_machine_learning/tree/main/day_10/data)

### First: Exploratory data analysis(EDA):
- We noticed that the most Type is Entire apartment.
- Most of guests pay less than 2000 RS for most types 9000 for Entire serviced apartment type.
- The price based on guests,	bedrooms,	beds and many services.

### Second: Data prep:
We remove the duplicate data ,we noticed some null values and replace it then we extract Categorical features.

### Third: Build KNeighborsRegressor Model and Improve it:
We split our data to test and train data then make baseline model,then build the KNeighborsRegressor model and improve it by best parameters.
