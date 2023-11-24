# Hotel_Booking_Prediction
This project analyzes hotel booking data to build a model for predicting whether a hotel booking will be canceled.

# Data
The data comes from the Hotel Booking Demand dataset on Kaggle. It contains booking information for a city hotel and resort hotel, including features like:

Lead time
Arrival date
Number of adults/children/babies
Number of weekend/week night stays
Customer type
Required parking spaces
Previous cancellations
Booking changes
Average Daily Rate (ADR)
Etc.
Analysis
The analysis focused on:

# Data cleaning and preprocessing
**Exploratory data analysis**
Which countries do guests come from?
How much do guests pay per night?
What are the busiest months?
How long do people stay?
Feature encoding using mean encoding technique
Feature selection using Lasso to select most important features
Outlier detection and removal
# Modeling
Multiple models were built and evaluated including:

Logistic Regression
Naive Bayes
Random Forest
Decision Tree
KNearest Neighbors
The Random Forest model performed the best with an accuracy of 96.5% on the test set.

# Conclusion
The model is able to predict whether a hotel booking will be canceled with high accuracy. This can help hotels better understand booking behavior and plan accordingly.

 
