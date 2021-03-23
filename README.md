# Linear-Regression-Model-on-1990-California-Housing-Prices

For this project, a simple Linear Regression Model is created for the 1990 California Housing value dataset. 

## Dataset and Library
Scikit Learn's LinearRegression class from the linear_model module was used to create this model.
The dataset consisted of 20640 rows of median housing values with 10 columns, as seen in the image below.
Please find the dataset in the following link: https://www.kaggle.com/camnugent/california-housing-prices?select=housing.csv

## Results
Based on the scatter plot, the relationship between the predicted values and the label values are fairly linear for the most part. In addition, the histogram of the residuals (y_test minus predictions) look similar to a normal distribution, indicating that linear regression was a decent choice for this model.
Lastly, the Mean Absolute Error and Root Mean Squared Error show that the prediction results were off by $50104 and $69079 respectively when predicting the housing price. This is a decent error when considering the housing prices can scale up to $500001.

Please visit the following link for the resulting images: https://hjmok.github.io/josephmok_portfolio/#/CH
