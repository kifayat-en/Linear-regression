# Linear-regression

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



