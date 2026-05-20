# EMBEDDED METHODS IN FEATURE SELECTION

## CONCEPTS LEARNED
- Embedded methods perform feature selection during model training.
- L1 regularization shrinks weak feature coefficients to zero.
- Feature importance is learned automatically by the model.
- `SelectFromModel()` automates feature removal using learned coefficients/importances.

## IMPORTANT METHODS / FUNCTIONS
- `LogisticRegression()`
- `SelectFromModel()`
- `l1_ratio`
- `C`
- `solver`
- `max_iter`
- `fit_transform()`
- `get_feature_names_out()`

## REAL WORLD CONCEPTS
- Embedded methods are faster than wrapper methods because feature selection happens during training itself.
- Tree-based feature importance is heavily used in production tabular ML systems.
- Scaling requirements depend on the model, not the dataset.
- `SelectFromModel()` is commonly used in ML pipelines to automate feature selection.
