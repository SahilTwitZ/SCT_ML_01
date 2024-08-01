# House Price Prediction Project

This project involves predicting house prices in India using linear regression. The dataset used for this analysis includes features such as the number of bathrooms, number of bedrooms, and living area. Below is a step-by-step explanation of the process and the results.

## Project Overview

The main objective of this project is to build a linear regression model to predict house prices based on certain features of the house.

## Steps and Process

### 1. Import Libraries

We begin by importing the necessary libraries for data manipulation, visualization, and model building.

### 2. Load and Explore the Data

We load the dataset and explore its structure, including the number of rows and columns, data types, and basic statistics. We also check for missing values and duplicates.

### 3. Correlation Analysis

We calculate the correlation matrix to understand the relationships between the features and the target variable (`Price`). This helps in selecting the most relevant features for the model.

### 4. Prepare the Data for Modeling

We select the relevant features (number of bathrooms, number of bedrooms, and living area) and the target variable (Price) for our model.

### 5. Split the Data

We split the data into training and testing sets to evaluate the model's performance on unseen data.

### 6. Build and Train the Model

We create and train a linear regression model using the training data.

### 7. Make Predictions

We use the trained model to make predictions on the test data.

### 8. Visualize the Results

We visualize the actual vs. predicted prices to assess the model's performance. This involves plotting the actual prices against the predicted prices.

### 9. Evaluate the Model

We evaluate the model using Mean Squared Error (MSE) and R-squared (R2) metrics to quantify the model's accuracy and goodness of fit.

## Results

- **Mean Squared Error (MSE):** This metric measures the average squared difference between actual and predicted values. A lower MSE indicates a better fit.
- **R-squared (R2):** This metric indicates the proportion of variance in the dependent variable that is predictable from the independent variables. A higher R2 value indicates a better fit.

## Conclusion

This project demonstrates a basic linear regression model to predict house prices based on selected features. Further improvements can be made by including more features, using different models, and performing hyperparameter tuning.
