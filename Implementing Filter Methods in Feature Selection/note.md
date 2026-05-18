# FILTER METHODS IN FEATURE SELECTION

## CONCEPTS LEARNED
- Importance of Feature Selection in High-Dimensional Data
- Difference Between Filter Methods for Categorical and Numerical Features
- Why Encoding is Required Before Applying Chi-Square Test
- How Feature Selection Helps Reduce Noise and Improve Learning

## IMPORTANT METHODS / FUNCTIONS
- `SelectKBest()`
- `VarianceThreshold()`
- `chi2`
- `mutual_info_classif`

## REAL-WORLD CONCEPT
- `mutual_info_classif` can capture nonlinear relationships in messy real-world data
- `chi2` works only with non-negative encoded categorical features
- Feature selection methods compare features against the target variable
- Different data types require different statistical selection methods
