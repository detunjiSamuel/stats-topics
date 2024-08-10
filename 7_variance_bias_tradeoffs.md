

## Explain the bias-variance tradeoff with regards to building and choosing a model to use?


**Bias** is the error produced by applying complex real world data using a simplified model.

High bias can led to underfitting  , meaning the model is to simple to capture underlying pattern in data.


**Variance** is the sensitivity of a model to changes in the training data .

High variance can led to over fitting , meaning the model learns the underlying pattern in the data so well , it feels to correctly handle new unseen data.


#### Trade Off

With more complex models ,
 - the bias will reduce and the model will be better able to fit the data 
 - the variance will also increase causing the model to be more sensitive to change


 Example

a) High Bias (Simple Model):

Example: A linear regression model using a subset of data as features
Pros: Easy to interpret, less likely to overfit
Cons: Might miss important patterns, potentially unfair to certain groups

b) High Variance (Complex Model):

Example: A deep neural network using all available features, including irrelevant
Pros: Can capture complex relationships in the data
Cons: Might learn noise, could make decisions based on irrelevant or sensitive features

#### Finding the right balance

- Start with a simple model and gradually increase complexity
- Use techniques like cross-validation to assess model performance




