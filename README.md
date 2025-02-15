# Car Price Prediction using Random Linear Regression and Lasso

## Overview
This project builds a machine learning model to predict the price of cars using **Random Linear Regression** and **Lasso Regression**. The dataset includes various car attributes that influence their price, such as mileage, engine size, and brand.

## Dataset
The dataset used for this project contains features like:
- Car brand
- Model year
- Engine size
- Mileage
- Fuel type
- Transmission type
- Number of doors
- Horsepower
- Price (target variable)

## Dependencies
To run this project, install the required Python libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Implementation Steps
1. **Data Preprocessing**
   - Load the dataset using pandas.
   - Handle missing values and outliers.
   - Encode categorical features using One-Hot Encoding.
   - Normalize or standardize numerical features if needed.
   
2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships between features and price.
   - Identify correlations using heatmaps.
   - Plot histograms and boxplots for insights.
   
3. **Model Training**
   - Split the dataset into training and testing sets.
   - Train models using **Random Linear Regression** and **Lasso Regression**.
   - Optimize hyperparameters using GridSearchCV.
   
4. **Evaluation**
   - Calculate performance metrics such as RMSE, MAE, and R².
   - Compare model results to determine the best approach.
   
## Usage
Run the following script to train and evaluate the model:
```bash
python train_model.py
```

## Results
- The best-performing model achieves an R² score of **XX%**.
- Important factors affecting car price include **brand, engine size, and mileage**.

## Conclusion
This project successfully predicts car prices using **Random Linear Regression** and **Lasso Regression**, demonstrating how different regression techniques perform in price estimation tasks.
# CarPricePrediction
