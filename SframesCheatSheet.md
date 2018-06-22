# SFramesCheatSheet





| Sample Command        | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
| import graphlab  | Library for graphlab | |   |
| dataset.show() | Shows a detailed page of dataset in a cool tab    |    |   |
| graphlab.canvas.set_target('ipynb') | prints output to notebook  |   |   |
| sales.show(view="Scatter Plot", x="sqft_living", y="price") | draws a scatterplot of the data with given properties |   |   |
| print test_data['price'].mean()   | calculate average for the price column  |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |


| Plotting       | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
| import matplotlib.pyplot as plt  | import pyplot as plt | |   |
| %matplotlib inline   | prints output to jupyter notebook  |   |   |
|plt.plot(test_data['sqft_living'],test_data['price'],'.',test_data['sqft_living'],sqft_model.predict(test_data),'-')   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |




```
graphlab.linear_regression.create(train_data, target='price', features=['sqft_living'],validation_set=None)
* .create -> creates a new linear regression model using graphlab; 
* following parameters are used 
* we can give any feture defined
```


| REGRESSION        | Explanation           | Notes  | Notes |
| ------------- |:-------------:| -----:| ---------:|
|sqft_model.evaluate (test_data) | Gives max and RMS errors  |   |   |
|sqft_model.predict (test_data)   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |









