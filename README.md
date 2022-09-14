#### statsmodels|sklearn|matplotlib|pandas|numpy
#### ols|LinearRegression|LeaveOneOut|Kfold|train_test_split

**Task :** build a simple linear regression model to predict delivery time using sorting time

**Summary :** 
I build a simple linear regression model using :
+ ols method
+ LinearRegression

I used ols to understand some basic terms like R-squared, adj. R-squared,  AIC, significance of p-value. 
Further I build model using LinearRegression. The techniques I used in building model are - LeaveOneOut, Kfold, train_test_split to compare all these with the same dataset.

**Conclusion :**
+ Model build using ols has R-squraed = 68% and LinearRegression have accuracy approximately in the line of 60's.
+ All the three techniues - LeaveOneOut, Kfold, train_test_split give approximately same accuracy except KFold (33%).
+ Accuracy remain in the line of 60's because we use a very small dataset (21 records).
