# Pandas Beginners
  DataFrame:is a table like sheet in Excel.
  A single column is stored in a *Series*
## `pd.describe()`
  - count: how many rows have non missing values
  - mean: average
    - std: standard deviation measures how numerically spread out the values are.
  - min, 25%, 50%, 75% and max: imagine sorting each column from lowest to highest value.
    - 25% : if you go quarter way through the list, you'll get a number that is bigger than 25% of the values and smaller than 75% of the values. That is the *225% percentile*
## Dot Notation for choosing "Prediction Target"
y=pd.Price

## Selecting with column list, to select "features"
- features=['Rooms','Bathroom','Landsize','Lattitude','Longitude']
- X=pd[features]
