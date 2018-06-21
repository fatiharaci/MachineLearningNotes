# Linear Regression

We are fitting a line through a data.

So our formula will be

```
fw (x) = w0 +w1*x
```
* w0 -> intercept
* w1 -> slope
* x -> regression coefficent
* w defines which line is the correct one

In order to decide which line is good for us we need to check how far away is our dots are so we use RSS (Residual Sum of Squares) as a control method:

```
RSS(w) = sqrt[(w1'-w1)^2 + (w2'-w2)^2 + (w3'-w3)^2+....]
```

But what if this is not a line; so we need to write a quadratic function:
```
fw (x) = w0 +w1*x + w2x^2
```
* x^2 -> this is accepted just an another element so it is also called as linear regression 


### Overfitting
Fitting the best may not be the best solution all the time. Minimizing RSS is the only problem here.


### How to choose prediction?
* Simulate Prediction
* In order to do that i need to train -> test set
* If we use test set we also need to check how we sucess so -> test curves / training error

### Machine Learning Parameters
* Weights (Regression Coefficients)
* Quality Metric -> error (RSS) Can happen many times


### Notes
*  The model that best minimizes training error is "NOT" the one that will perform best for the task of prediction on new data.

