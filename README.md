About the Project
This project is a comprehensive machine learning study aimed at accurately predicting the prices of used cars based on their features in a given dataset. The project includes the steps of analyzing the dataset, comparing different machine learning models, and optimizing the best-performing model.

Methodology:

Data Preparation: The project started with the CarPrice_Assignment (1).csv dataset. Inconsistent or erroneous brand names in the CarName column were cleaned and standardized. Categorical data (such as fueltype, carbody) were converted into a numerical format suitable for models.

Model Comparison: Ten different regression models, including Random Forest Regressor, Gradient Boosting, Ridge, Lasso, and Linear Regression, were compared using RMSE and R-squared metrics to measure their performance. As a result of this comparison, the Random Forest Regressor was determined to be the best model, having the lowest error rate (1825.50 RMSE) and the highest R-squared value (0.958).

Hyperparameter Tuning: To further improve the performance of the selected Random Forest model, the hyperparameter tuning technique (GridSearchCV) was used. This process enabled the model to find the optimal combination of parameters (n_estimators=200, max_depth=10, etc.).

Project Outputs:

A detailed comparison table showing the performance metrics of different models.

Graphs visualizing the RMSE and R-squared values.

The final performance of the hyperparameter-tuned Random Forest Regressor model:

RMSE: 1804.60

R-squared: 0.9584

Reusable and well-commented Python code covering all project steps.

These outputs show that the model operates reliably and can predict new car prices with high accuracy.
