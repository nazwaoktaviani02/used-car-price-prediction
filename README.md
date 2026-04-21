Used Car Price Prediction
This repository contains a machine learning project to predict the selling price of used cars using the CarDekho dataset. The project covers the full pipeline from data preprocessing to model hyperparameter tuning.

Objectives
> Perform Exploratory Data Analysis (EDA) to identify key price drivers.
> Build a regression model to estimate car prices based on features like year, mileage, and fuel type.
> Optimize model performance using grid search techniques.

Workflow
1. Data Preprocessing: Handled duplicates and verified data integrity.
2. Feature Engineering: Prepared categorical variables (Fuel Type, Seller Type, Transmission) for modeling.
3. Exploratory Data Analysis: Visualized feature correlations using Seaborn and Matplotlib.
4. Modeling: Implemented a Random Forest Regressor to handle non-linear relationships in the data.
5. Optimization: Used GridSearchCV to fine-tune hyperparameters.

Results
The optimized model reached its best performance with the following parameters:
> max_depth: 5
> n_estimators: 5

Tech Stack
> Language: Python
> Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib

How to Use
1. Clone the repository.
2. Ensure you have the dataset cardekho_data.csv in the root directory.
3. Run the used_cars_regression.ipynb notebook.