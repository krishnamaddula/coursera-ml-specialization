Linear regression model
fw(x) = W0 + W1 x where
    W0 -> Interceptor
    W1 -> Weight
    Also known as regression coefficients
f subscript w indicates that this function is specified by parameters w being set of w0 and w1

Cost for given line is going to help with Which w we want to choose for our model.

Residual sum of squares - RSS
  square of distance between Model prediction and the actual value

Linear function may not be good all the time.. Quadratic function might be a good fit for housing price analysis here.

fw(x) = w0 + w1 x + w2 x square.

Till is still called linear regression even though we are fitting the data to quadratic function.


There could be a better option than quadratic which is polynomial function.. or may not?

There is high porbability of overfitting the model with data with higher order polynomial functions.


Minimizing RSS doesnt mean that we have accurate predictions..It is possible that we have bad predictions (with overfitting model)

Training/Test Curve:

How to choose model order/complexity:??
   Simulate predictions: 
        Remove some houses from data set..  (test set)
        fit model on remaining houses.      (training set)
        and then run the heldout houses on the predicted model in above step.
        Compare with actual values

Training Error:  RSS for training set. Reduces as the model complexity increases
Test Error: RSS for test set. Increases as the model complexity increases.


Adding more features:  Can get us hyper plane model for prediction.


Machine Learning pipe line for Linear Regression:

Training Data -> Feature Extraction -> ML Model (Regression) -> Predicted house price ->>

Refer to image for more detailed pipeline

