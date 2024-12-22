# price_optimization
This project aims to optimize retail pricing by predicting the total price of products based on a variety of features

## Project Overview
Using historical sales data, the prject seeks to predict the total price of products in a way that maximizes revenue while considering factors such as product category, unit price, freight price, competitor prices, and other product attributes. The project leverages data exploration, feature engineering, and a decision tree regression model to achieve this objective.

## Project Objective
The goal of this project is to build a predictive model using decision trees to estimate the total price of retail products based on multiple input features.

## Methods
- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Model Training
- Model Evaluation
- Visualization

## Technologies Used  
Python Libraries:
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

## Key Findings
- There is a clear seasonal trend in sales, with fluctuations in both quantity sold (qty) and total price (total_price). Sales tend to vary across months.
- The analysis of competitor prices (comp_1, comp_2, comp_3) revealed that the price difference between a product's price and its competitors' prices varies significantly across product categories.
- The decision tree model identified that the most important features for predicting the total price are:  
● Quantity Sold (qty): This feature has the highest importance, which makes sense since more units sold directly affect total sales.  
● Lag Price: Past price data was also influential, highlighting the importance of historical pricing information.  
● Unit Price: The unit price was an important factor in determining the total price, but it had lower importance than quantity and lag price.
  
