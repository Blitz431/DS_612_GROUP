# Ana Sachuk – Cleaning, Visualization, and Modeling Contribution

## Data Cleaning Process
- Reviewed dataset structure and selected key variables related to price  
- Checked for missing values across columns  
- Removed columns with high missing values (condition, cylinders)  
- Dropped remaining rows with missing values to ensure a clean dataset  
- Filtered out unrealistic price values (e.g., price < 100 or extremely high values)  

## Data Visualization Process
- Created a histogram to visualize the distribution of vehicle prices  
- Identified strong skewness in price due to extreme outliers  
- Cleaned price values to produce a more meaningful and interpretable distribution  
- Used visualization to better understand price behavior before modeling  

## Modeling Process
- Selected key features for modeling (year as predictor, price as target)  
- Split data into training and testing sets  
- Tested multiple models:
  - Linear Regression  
  - Decision Tree Regressor  
  - Ridge Regression  
- Evaluated model performance using Mean Squared Error (MSE)  

## Key Findings
- Price distribution is highly skewed without cleaning due to extreme values  
- Decision Tree model performed better than Linear Regression and Ridge in this setup  
- Year alone is not a strong predictor of price, suggesting additional features are needed
