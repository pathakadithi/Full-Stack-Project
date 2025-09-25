🏡 House Price Prediction using Linear Regression
📌 Project Overview :

* This project applies Linear Regression to predict house prices based on various features (such as living area, number of rooms, location, etc.). The dataset was preprocessed, split into training and testing sets, and evaluated using multiple regression metrics.
⚙️ Steps Followed

1. Import & Preprocess Data
  * Loaded dataset using pandas.
  * Handled missing values and irrelevant columns.
  * Converted categorical variables into numeric form using one-hot encoding.

2. Train-Test Split
  * Split data into 80% training and 20% testing sets.

3. Model Training
  * Fitted a LinearRegression model from sklearn.linear_model.

4. Model Evaluation
  * Evaluated using:
    1. MAE (Mean Absolute Error)
    2. MSE (Mean Squared Error)
    3. RMSE (Root Mean Squared Error)
    4. R² score

5. Visualization
  * Plotted regression line (for single features like GrLivArea).
  * Compared actual vs predicted values.

6. Interpretation
  * Extracted model coefficients to understand feature importance.

📊 Results :
* The model was able to explain a significant portion of the variance in house prices (R² close to 1 on test data).

* Coefficients helped identify which features most strongly influence house prices.
