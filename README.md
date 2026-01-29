# Sales / Product Return Rate Analysis

## Project Overview
This project analyzes e-commerce sales and product return data to identify key drivers of high return rates.  
The goal is to help businesses reduce return risk and improve product and policy decisions using data-driven insights.

## Dataset
- 10,000 e-commerce orders
- Customer, product, pricing, discount, shipping, and return information

## Key Steps
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning modeling using Random Forest
- Model evaluation using Precision, Recall, and ROC-AUC

## Model Used
- Random Forest Classifier
- Handled class imbalance using class weighting
- Evaluated with confusion matrix and ROC curve

## Key Insights
- High discounts increase return probability
- Fast return behavior is a strong indicator of future returns
- Certain product categories show higher return rates
- Return delay (days to return) is the most important predictor

## Business Recommendations
- Monitor and restrict excessive discounts
- Flag high-value orders for stricter return policies
- Identify customers with fast return patterns
- Use early return-delay signals to predict high-risk orders

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Structure
