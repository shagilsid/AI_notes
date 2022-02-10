# Building Model
## Steps
1. Define: What type of model will it be?
2. Fit: Capture patterns from provided date. This is the heart of modelling
3. Predict: Predict
4. Evaluate: Determine how accurate the model's predictions are.

```python
from sklearn.tree import DecisionTreeRegressor

# Define model. Specify a number for random_state to ensure same results each run
melbourne_model = DecisionTreeRegressor(random_state=1)

# Fit model
melbourne_model.fit(X, y)
```

`random_state`: specifying a number ensures you get the same results in each run.


## Making predictions
```python
print("Making predictions for the following 5 houses:")
print(X.head())
print("The predictions are")
print(melbourne_model.predict(X.head()))
```
# Model Validation
How good your model is?
Measuring model quality is the key to iteratively improving models.

