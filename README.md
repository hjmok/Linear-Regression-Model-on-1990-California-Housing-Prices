# Linear-Regression-Model-on-1990-California-Housing-Prices

For this project, a simple Linear Regression Model is created for the 1990 California Housing value dataset. 

## Dataset and Library
Two separate models were created. The first one used Scikit Learn's LinearRegression class and second used PySpark's MLLib to get the LinearRegression module.
The dataset consisted of 20640 rows of median housing values with 10 columns, as seen in the image below.
Please find the dataset in the following link: https://www.kaggle.com/camnugent/california-housing-prices?select=housing.csv

## Results
Based on the scatter plot in the Scikit Learn notebook, the relationship between the predicted values and the label values are fairly linear for the most part. In addition, the histogram of the residuals (y_test minus predictions) look similar to a normal distribution, indicating that linear regression was a decent choice for this model.
Both the PySpark and Scikit Learn Linear Regression modules resulted in similar Root Mean Squared Errors at $71944 and $69079 respectively. This is within one standard deviation of the median housing price, which is $115396.

Please visit the following link for the resulting images: https://hjmok.github.io/josephmok_portfolio/#/CH
