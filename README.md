# Toronto_Crime_Rate_Predictor

This code creates a machine learning model and trains it for each unique neighborhood in a dataset. It uses linear regression to predict the number of crimes in a given year based on the number of crimes in previous years.

## Prerequisites
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
## Usage
- Load the dataset into a Pandas DataFrame.
- Run the code.
- The code will create a model and train it for each unique neighborhood in the dataset.
- The model will predict the number of crimes in the years 2019-2024.
- The code will plot the training data, the prediction data, and the linear regression training line and prediction line for each neighborhood.
- The root mean squared error (RMSE) between the predicted values and actual values will be displayed on the x-axis.
## Code Explanation
- The code loops through each unique neighborhood in the dataset.
- For each neighborhood, it creates an array of years and an array of crimes.
- It then creates a linear regression model and fits it to the data.
- The code then plots the training data, the prediction data, and the linear regression lines.
- Finally, the code predicts the number of crimes for the years 2019-2024 and calculates the RMSE.
