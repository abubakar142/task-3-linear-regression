# Task 3 - Linear Regression

## Objective

The objective of this task is to implement and understand simple and multiple linear regression using Python.

## Tools Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Dataset

A House Price Prediction dataset was used for this project.

### Features

* Area
* Bedrooms

### Target

* Price

## Steps Performed

1. Imported the dataset using Pandas.
2. Checked the dataset for missing values and basic statistics.
3. Selected features and target variable.
4. Split the dataset into training and testing sets.
5. Created a Linear Regression model using Scikit-learn.
6. Trained the model using the training data.
7. Generated predictions on the test data.
8. Evaluated the model using:

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * R² Score
9. Analyzed the regression coefficients.
10. Created a regression visualization using Matplotlib.

## Results

The model performance was evaluated using MAE, MSE, and R² score.

The coefficients were also analyzed to understand how the input features affect the predicted house price.

## Files

* `dataset.csv` - Dataset used for the project
* `linear_regression.py` - Python implementation
* `regression_plot.png` - Regression visualization

## Conclusion

Linear Regression was successfully implemented to predict house prices based on house area and number of bedrooms. The evaluation metrics were used to measure the performance of the model.
