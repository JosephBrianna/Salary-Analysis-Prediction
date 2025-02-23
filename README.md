
# README: Salary Analysis & Prediction

## Description

This script showcases a thorough analysis of employee salaries from a CSV file named `salaries.csv`. Visualizations such as bar charts, box plots, histograms, scatter plots, and heatmaps are employed to provide insights on various facets of the data, such as salary distributions, company size distributions, relationships between variables, etc.

The latter part of the script leverages the Random Forest Regressor from `scikit-learn` to predict employee salaries based on multiple features.

## Dependencies:

To run this script, ensure the following libraries are installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Instructions:

1. Ensure you have `salaries.csv` in the same directory as the script.
2. Run the script.
3. Initially, the script will load the data and display various visualizations providing insights about salary distributions, company sizes, etc.
4. After the visualizations, the script will preprocess the data, train a Random Forest model, and predict employee salaries. Performance metrics such as Mean Squared Error (MSE) and R-squared (R2) will also be displayed.

## Analysis Overview:

- Load the CSV data into a pandas DataFrame.
- Display a snapshot of the data using `head()`.
- Visualize:
  - Median salary by job title.
  - Salary distribution by job title and experience level.
  - Company sizes distribution.
  - Salary distribution.
  - Relationship between salary and remote work ratio.
  - Correlations among numeric attributes.

## Salary Prediction:

1. Data Preprocessing:
   - Handle missing values.
   - Encode categorical variables.
   - Split data into training and testing sets.

2. Model Training:
   - Use a Random Forest Regressor to train on the dataset.

3. Model Evaluation:
   - Evaluate the model using Mean Squared Error (MSE) and R-squared (R2).

4. Salary Prediction:
   - Predict salaries for sample records and compare them with the actual salaries.

## Note:

Make sure to adapt paths and column names if your dataset is different from the one specified in this script. 

---

That's a concise README that gives a clear overview of what the script does and how to use it. You can further expand on sections like 'Data Preprocessing', 'Model Training', etc., based on the specific requirements or further details you'd like to provide to the end-users.
