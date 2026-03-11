# House Price Prediction

This project builds a machine learning model to predict house prices using the Ames Housing dataset from the Kaggle competition House Prices: Advanced Regression Techniques.

The goal is to estimate the SalePrice of a house based on various features such as size, quality, location, and construction details.

## Project Structure
House-price-prediction
| 
## Project Structure

*   `house_prices_eda.ipynb/`:  Exploratory Data Analysis
*   `house_price_model.ipynb/`:  Data preprocessing and model training
*   `README.md/`

## Workflow

The project follows a typical machine learning pipeline:

1. Data loading
2. Exploratory Data Analysis (EDA)
3. Handling missing values
4. Feature engineering
5. Encoding categorical variables
6. Model training
7. Model evaluation

## Models

The task is a regression problem, where the goal is to predict a continuous value (house price).

Typical models used:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metric

Model performance is evaluated using RMSE (Root Mean Squared Error), which measures the average difference between predicted and actual house prices.

Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook