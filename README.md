The following preprocessing and changes were performed on the California Housing dataset
**Dataset Loading**
The California Housing dataset was loaded using fetch_california_housing() from sklearn.datasets.
**DataFrame Conversion**
The dataset was converted into a Pandas DataFrame using the provided feature names as column names.
**Target Variable Added**
The target variable, MedHouseVal, was added to the DataFrame as the dependent variable.
**Missing Value**
The dataset was checked for missing values using isnull().sum(). The dataset did not contain missing values, so no imputation was required.
**Feature and Target Separation**
The input features were separated into X, while MedHouseVal was used as the target variable y.
**Train-Test Split**
The dataset was divided into 80% training data and 20% testing data.
**Feature Scaling**
StandardScaler was used to standardize the features. Scaling was particularly important for algorithms such as Linear Regression and SVR, where differences in feature scales can affect the model.
**Regression Models Implemented**
Five regression algorithms were implemented:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
**Model Evaluation**
Each model was evaluated using:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared (R²)
**Model Comparison**
The models were compared based on their evaluation metrics. Lower MSE and MAE and higher R² indicate better predictive performance.
