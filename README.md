# Gold Price Prediction Project

**Objective:**

This project aims to predict the price of gold using various economic indicators. The dataset contains historical data on several financial variables such as the S&P 500 Index (SPX), the price of crude oil (USO), the price of silver (SLV), and the EUR/USD exchange rate. The goal is to understand the relationship between these variables and the price of gold (GLD) and to build a predictive model that can accurately forecast the price of gold.

[Link to dataset](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data)

**Overview of the Process:**

1. Data Collection:

   * Importing the dataset containing economic indicators and gold prices

2. Data Analysis and Preprocessing:

   * Examined dataset structure and summarized key statistics.
   * Checked for and handled any missing values.
   * Performed correlation analysis to understand relationships between features.
   * Visualized the distribution of the gold price (GLD).

3. Feature Selection:

   * Selected relevant features (SPX, USO, SLV, EUR/USD) and the target variable (GLD).

4. Model Training:

   * Split the data into training and testing sets.
   * Trained a Random Forest Regressor model on the training data.

5. Model Evaluation:

   * Evaluated the model's performance on both training and test data using R2 score and Mean Absolute Error (MAE).
   * Visualized and compared the actual vs. predicted prices for both training and test data.

6. Predictive System:

   * Developed a system to predict gold prices based on input economic indicators using the trained model.
