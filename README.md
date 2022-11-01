
# Lasso-Ridge-House-Prediction

> This programming assignment wherein you have build a Lasso-Ridge regression model for the prediction of house pricing.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

The company wants to know: i) Which variables are significant in predicting the price of a house. ii) How well those variables describe the price of a house

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test but we use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.

Always uses the simple and robust model for better performance on real world data.

####  Higher values of +ive co efficients suggest a increase in sale value.
#### Few features for positive co efficient are:-
 |  Feature  |  Description  |
 |  ---  |  ---  |
 |  GrLivArea  |  Above grade (ground) living area square feet  |
 |  OverallQual  |  Rates the overall material and finish of the house  |
 |  OverallCond  |  Rates the overall condition of the house  |
 |  TotalBsmtSF  |  Total square feet of basement area  |
 |  GarageArea   |Size of garage in square feet  |
        
#### Higher values of -ive co efficients suggest a decrease in sale value.
#### Few features for negative co efficient are:-
   |  Feature  |  Description  |
   |  ---  |  ---  |
   |  BuiltOrRemodelAge  |  Age of the property at the time of seeling  |
   |  MSSubClass  |  Identifies the type of dwelling involved in the sale  |
   
   
### Whenever the predicted sale price is lower than the market value, you can plan your purchase of property.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- statsmodels
- sklearn
- etc 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by 

- [@HariHaran0690] haran.jayan1@gmail.com

Please feel free to contact me! Happy Coding !!

