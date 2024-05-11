# Prediction-for-Average-bottom-hole-pressure-in-Volve-field
Lasso regression model 

**Data cleaning and processing**
The datasets were subjected to data cleaning to ensure no missing values or NaN values to prevent any distortion in the statistical analyses and machine learning models, leading to biased results or inaccurate predictions. Therefore, the rows with missing values were dropped from the datasets and not used in the analysis, also rows with zero entries were removed from the dataset. The natural logs of all the features were taken to enable standardization of the data. The total count of the rows and columns used for the analysis (4166, 11) respectively which contained non-null values.

**Based on the results obtained from the analysis outlined in the methodology section of this work the following conclusions can be drawn:**

a. The datasets affecting the bottom-hole pressure were filtered and successfully correlated as shown on the heat map.
 
b. A lasso regression model and Multiple linear regression model were successfully developed. 
 
c. The bottom-hole pressures of the Volve field were successfully predicted using the lasso regression and Multiple linear regression models. They produced a high degree of coefficient of determination of 78% and 78.6% respectively.  This suggests that both models are good for predicting average bottom-hole pressure.

d. All features contributed significantly to the model except bore gas volume.
