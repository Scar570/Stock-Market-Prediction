# Stock Market Prediction using Numerical and Textual Analysis

Objective:
The main objective of this project is to create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices and sentimental analysis of news headlines.

Steps:
Step 1: Stock Price Analysis and Prediction
1.1 Importing Required Libraries for numerical analysis and prediction of stock prices.
1.2 Importing the Numerical dataset and performing Exploratory Analysis.
1.3 Creating a dataframe for storing the Closing stock data per day.
1.4 Data Normalization and Division into Training and Test sets.
1.5 Creating a LSTM Neural Network Model for Numerical Analysis.
1.6 Making Predictions of the Model.

Step 2: Textual Data (News Headlines) Analysis
2.1 Importing Required Libraries for Textual (News Headlines) analysis.
2.2 Importing the Textual dataset and performing Exploratory Analysis.
2.3 Representing the number of headline texts (News Headline) per city.
2.4 Representing Number of News Headlines per year and per city.
2.5 Sentiment Analysis of News Headlines.

Step 3: Creating a Hybrid model
3.1 Importing Required Libraries.
3.2 Importing the Numerical and Textual dataset.
3.3 Creating Hybrid data from Numerical and Textual Data.
3.4 Performing Sentiment Analysis on Hybrid Data.

3.4.1 Sentiment Analysis using TextBlob.
3.4.2 Adding subjectivity and polarity Scores to Textual Data (News Headlines).
3.4.3 Visualizing the polarity and Subjectivity scores.
3.4.4 Performing Sentiment Analysis over the news Headlines of Hybrid Data.
3.5 Training and Testing the Models for Stock Price/Performance Analysis.
3.5.1 Stock Price/Performance analysis using Logistic Regressor Model.
3.5.2 Stock Price/Performance analysis using Random Forest Model.
3.5.3 Stock Price/Performance analysis using Decision Tree Model.
3.5.4 Stock Price/Performance analysis using Linear Discriminant Analyser Model.
3.5.5 Stock Price/Performance analysis using AdaBoost Model.
3.5.6 Stock Price/Performance analysis using Logistic Gradient Boosting Model.
Conclusion:
Six different Neural Network models were used for the analysis and prediction of stock price/performance, trained with Hybrid data generated from Numerical and Textual data. The accuracy of each model is as follows:

Logistic Regression Model: 83.22%
Random forest Model: 81.20%
Decision Tree Model: 79.31%
Linear Discriminant Model: 83.45%
AdaBoost Model: 85.36%
Gradient Boosting Model: 85.52%
The Gradient Boosting Model outperforms the other models with an accuracy of 85.52% in the analysis and prediction of stock price/performance.
