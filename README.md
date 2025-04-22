# Spinal Attribute Regression Analysis

This project applies a simple linear regression model to analyze the relationship between **pelvic incidence** and **pelvic tilt**, two important features in spinal biomechanics.

## Project Overview
- Dataset: 'column_3C_weka.csv'
- Task: Predict 'pelvic_tilt' based on 'pelvic_incidence'
- Method: Simple Linear Regression
- Visualization: Correlation heatmap and regression line plot

  ## Steps Performed
  1. Load and inspect the dataset
  2. Visualize feature correlation with a heatmap
  3. Select two spinal-related features for analysis
  4. Split the dataset into training and test sets
  5. Train a linear regression model
  6. Plot the regression results
 
  ## Dataset
  Ensure 'column_3C_weka.csv' is placed in the same directory as the notebook. It must include at least the columns:
  - 'pelvic_incidence'
  - 'pelvic_tilt'
 
  ## Requirements
  - Python 3.x
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
