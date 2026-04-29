## Data Cleaning
- Reviewed dataset structure and selected key variables related to price
- Checked for missing values across columns
- Removed columns with high missing values (condition, cylinders)
- dropped remaining rows with missing values to ensure a clean dataset
- Filtered out unrealistic prices, capping the range to $500-$150,000 to remove data-entry errors (raw maximum was ~$3.7 billion)
- Converted 'year' from float to int after cleaning
## Data Visualization
- created actual vs. predicted scatterplots for both models to compare fit quality
- generated feature importance bar chart for Random Forest model to identify strongest price predictors
- plotted coefficient bar chart for Multiple Linear Regression model to identify strongest price indicators
## Modeling Process
- selected price as target variable for both models and year, manufacturer, model, region, and state as predictors
- one-hot encoded the model column to avoid the assumption of ordinal relationships between model names and grouped the top 200 models to minimize amount of columns while preserving popular models
- label encoded manufacturer, region, and state for the feature matrix
- Tested two models:
  - Random Forest
  - Multiple Linear
- Evaluated both models using mean absolute error (MAE), roor mean square error (RMSE), and R2
## Key Findings
- Price distribution is highly skewed without cleaning due to extreme values
- one-hot encoding significantly improved performance of the Random Forest model compared to label encoding
- Random Forest outperforms Multiple Linear model confirming that pricing has strong non-linear structure
- year is the strongest price indicator followed by manufacturer based on the feature importance chart
