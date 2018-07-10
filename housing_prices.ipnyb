import pandas as pd

main_file_path = '../input/house-prices-advanced-regression-techniques/train.csv' # this is the path to the Iowa data that you will use
data = pd.read_csv(main_file_path)

# Run this code block with the control-enter keys on your keyboard. Or click the blue botton on the left
print(data.describe())
print(data.columns)

price_data = data.SalePrice
print(price_data.head())

cols = ['Neighborhood', 'Street', 'Utilities']
three_cols_of_data = data[cols]
print(three_cols_of_data.describe())
