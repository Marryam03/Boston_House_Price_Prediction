# Boston_House_Price_Prediction
This code is a machine learning project that aims to predict house prices in Boston based on various features using different regression models.

1) Data Loading and Exploration:
- Imported the necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.
- Loaded a dataset containing information about Boston house prices.
- Created a correlation heatmap to visualize the relationships between different features.

2) Outliers Analysis:
- Generated a boxplot to analyze and visualize potential outliers in the dataset.

3) Data Preprocessing:
- Data preprocessing steps by standardizing the feature data using StandardScaler.
- The dataset is split into training and testing sets using train_test_split.

4) Model Building and Evaluation:
- Function 'model' is used to train, evaluate, and visualize different regression models.
- It trained four different regression models: Linear Regression, Decision Tree Regressor, Support Vector Regression (SVR), and Gradient Boosting Regressor.
- For each model, I printed the accuracy, Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

6) Best Model:
-The best model based on the evaluation is "Gradient Boosting," as it has the lowest MAE (2.03), MSE (7.68), and RMSE (1.43), and the highest R2_score (0.91) which is closer to 1. This indicates that the Gradient Boosting Regressor provides the most accurate predictions for Boston house prices compared to the other models evaluated in this project.
