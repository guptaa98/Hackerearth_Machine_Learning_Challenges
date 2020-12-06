1. Read all the csv files in train,test and saple_submission respectively
2. Checked the length of train and test files.
3. Checked for missing values in train and test by using 'missingno.matrix' from missingno library.
4. Converted the values in 'Loyalty_customer' into 0 and 1 having loyalty as yes and no respectively.
5. Converted the categories of 'Product_Category' into values from 0-9.
6. Replaced the missing values with median.
7. Extracted the date,month,year,hours,minute from 'instock_date' feature.
8. Checked for the skewness of the features in train and test dataset and used lognormal transformation on them.
9. Applied GradientBoostingRegressor algorithm on the data for predictions. 
10.Finally made the file submission ready. 
