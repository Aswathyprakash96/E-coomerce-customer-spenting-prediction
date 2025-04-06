🛍️ Ecommerce Customer Spending Prediction
This project uses linear regression to predict how much a customer is likely to spend in a year based on their interaction with an ecommerce platform.
📁 Dataset
Source: Ecommerce Customers.csv
This dataset contains information about customers such as:
Avg. Session Length
Time on App
Time on Website
Length of Membership
Yearly Amount Spent (Target)
🧠 Objective
To build a regression model that accurately predicts Yearly Amount Spent based on user behavior metrics.
🔍 Steps Followed
Data Loading & Inspection
Checked for nulls, duplicates, and datatypes using df.info(), df.describe(), and df.isnull().sum()
Data Cleaning
Removed irrelevant features like Email, Address, and Avatar (if present)
Converted Age to integer if needed
Exploratory Data Analysis (EDA)
Scatterplots and regression lines using sns.lmplot() for feature vs. target
Correlation heatmap to evaluate feature importance
Feature Selection
Selected numerical columns with the most correlation to the target
Model Building
Applied Linear Regression using sklearn.linear_model.LinearRegression
Evaluation
Used metrics like:
Mean Squared Error (MSE)
R² Score
Visualized predictions vs actual values
Prediction on New Data
Tested the model with custom user input using a single row of feature data
🔧 Tech Stack
Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-learn
📊 Sample Output
bash
Copy
Edit
MSE: 30.29
R² Score: 0.83
Predicted Yearly Amount Spent: $498.45
