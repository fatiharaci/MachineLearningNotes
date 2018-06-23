## SFramesCheatSheet

| Sample Command        | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
| import graphlab  | Library for graphlab | |   |
| dataset.show() | Shows a detailed page of dataset in a cool tab    |    |   |
| graphlab.canvas.set_target('ipynb') | prints output to notebook  |   |   |
| test_data['price'].mean()   | calculate average for the price column  |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |


## Python Commands

| Python Commands       | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
| %matplotlib inline   | prints output to jupyter notebook  |   |   |



## Plotting
### Pyplot
```
import matplotlib.pyplot as plt 
plt.plot( test_data['sqft_living'],test_data['price'],'.',
          test_data['sqft_living'],sqft_model.predict(test_data),'-')        
```
* price is drawn with "."
* predicted prices id drawn with "-"


### ScatterPlot
```
sales.show(view="Scatter Plot", x="sqft_living", y="price")
```

### BoxWhisker Plot
```
sales.show(view='BoxWhisker Plot', x='zipcode', y='price')
```
Draws in two; x and y ; x of the value holds values of y in a line; 

### Linear_Regression

```
graphlab.linear_regression.create
                             (train_data, 
                              target='price', 
                              features=['sqft_living'],
                              validation_set=None)
```

* .create -> creates a new linear regression model using graphlab; 
* following parameters are used 
* we can give any feture defined


| REGRESSION        | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
|model.evaluate (test_data) | Gives max and RMS errors  |   |   |
|model.predict (test_data)   | It gives predicted output for the <test_data>  |   |   |
|model.get ('coefficients')   | Gives coefficients/weights   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |









