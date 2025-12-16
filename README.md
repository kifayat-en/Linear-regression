# Linear-regression
**Linear regression is a fundamental statistical and machine learning method that models the relationship between variables by fitting a straight line (or hyperplane for multiple variables) to data, aiming to predict a dependent variable (outcome) from one or more independent variables (predictors). It finds the "line of best fit" that minimizes errors, allowing for predictions, such as forecasting sales from advertising spend or exam performance from study time, with simple regression having one predictor and multiple regression having several.**

`Multiple Linear Regresssion with graphs and LR metrics`

**MAE — Mean Absolute Error**

**Formula: MAE = average(|actual − predicted|)**

Tells on average how much your prediction is wrong.     
Uses absolute difference.       

Example     
Actual = 100     
Predicted = 90      
Error = |100 − 90| = 10     

If MAE = 8        
model is wrong by 8 units on average      
**Advanateges:**      
`Easy to understand`     
`Same unit as target`

**Disadvantages:**      
`Treats small & big errors same`
<hr>

**MSE — Mean Squared Error**      

**Formula: MSE = average((actual − predicted)²)**       

Same as MAE but squares the error      
Big mistakes are punished more.      

**Example**      
Errors: 2 and 10     
MAE = (2 + 10)/2 = 6       
MSE = (4 + 100)/2 = 52       

**Advantages:**      
`Good when big errors are dangerous`       

**Disadvantages:**        
`Units become squared`         
`Hard to interpret`           



