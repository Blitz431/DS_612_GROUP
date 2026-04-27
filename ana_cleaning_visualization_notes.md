# Ana Sachuk – Cleaning & Visualization Contribution

## Data Cleaning Process
- Reviewed dataset structure and identified key variables related to price
- Checked for missing values in important columns (price, year, odometer)
- Removed or flagged listings with unrealistic prices (e.g., price = 0)
- Identified extreme outliers in price and mileage
- Considered removing duplicate listings
- Reviewed categorical variables (condition, fuel, transmission, manufacturer)
- Identified columns that may not be useful for modeling

## Data Visualization Process
- Planned visualizations to explore relationships:
  - Price distribution (histogram)
  - Price vs. year of car
  - Price vs. mileage (odometer)
  - Average price by manufacturer
  - Average price by condition
- Focused on understanding trends before applying models

## Initial Observations
- Newer cars tend to have higher prices
- Lower mileage is associated with higher prices
- There are significant outliers that could impact model performance
- Some categorical features likely influence price (e.g., condition)
