# Salary-regression-task

## Overview

This Jupyter Notebook, `Regression Task.ipynb`, focuses on exploring and implementing a simple linear regression model to predict salaries based on years of experience. The dataset used for this analysis is named `Salary_dataset.csv`.

## Key Steps

1. **Data Exploration:**
   - Loaded the dataset and performed an initial examination.
   - Checked for missing values, duplicates, and basic statistics of the numerical columns.
   - Utilized histograms to visualize the distribution of years of experience and corresponding salaries.

2. **Data Modeling:**
   - Selected the predictor (`X`) and target (`y`) variables.
   - Split the data into training and testing sets.
   - Implemented a baseline model using Linear Regression.
  
3. **Baseline Model Evaluation:**
   - Calculated Mean Squared Error (MSE), R-squared, and Root Mean Squared Error (RMSE) to assess model performance.
   - Visualized the predictions against actual values using a scatter plot.

4. **Exploration of Ridge Regression:**
   - Explored Ridge regression as an alternative, utilizing hyperparameter tuning through GridSearchCV.
   - Found that the Ridge model didn't improve upon the baseline model, and hence the simpler linear regression model was chosen as the final model.

## Results

- **Baseline Model:**
  - R-squared: 93%
  - RMSE: 0.685

- **Ridge Model (Optional):**
  - Best alpha: 0.1
  - MSE: 0.469
  - R-squared: 93%
