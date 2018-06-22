# SFramesCheatSheet


## Sframes


```
import graphlab
```
Library for graphlab

---






```
<dataset>.show()
```
Shows a detailed page of dataset in a cool tab

---



```

graphlab.canvas.set_target('ipynb')
sales.show(view="Scatter Plot", x="sqft_living", y="price")
```

draws a scatterplot of the data

---





```
sqft_model = graphlab.linear_regression.create(train_data, target='price', features=['sqft_living'],validation_set=None)

```

.create -> creates a new linear regression model using graphlab; following parameters are used:
* we can give any feture defined.
* above example uses sqft_living

---





