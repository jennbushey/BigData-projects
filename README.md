### Table of Contents

[Data Analytics](#data-analytics)

[Big Data](#big-data)

# Data Analytics

## [Time Series Forecasting with Yahoo Stock Price](./time-series-stocks.ipynb)

The objective of this project was to predict stock prices using historical stock market data and machine learning techniques, specifically using a Ridge Regression model.

The dataset consisted of daily stock market data, including features such as High, Low, Open, Volume, Adj Close, Close, and Date. Data exploration and preprocessing steps were performed to prepare the data for modeling.

Exploratory Data Analysis (EDA) was conducted to understand the distribution and relationships between variables. Feature engineering techniques were used to create lagged features, rolling statistics, and other relevant features to improve model performance. A Ridge Regression model was selected and trained on the preprocessed dataset. The model was evaluated using metrics such as R2 Score, Mean Absolute Percentage Error (MAPE) and Root Mean Squared Error (RMSE).

The Ridge Regression model showed promising results in predicting stock prices. Evaluation metrics indicated that the model performed well in predicting stock prices based on the selected features.

Future steps for this project include fine-tuning the model's hyperparameters, exploring other machine learning algorithms, and incorporating additional features or data sources to further improve prediction accuracy. Overall, this project demonstrates the feasibility of using machine learning for stock price prediction, with potential applications in real-time market analysis and decision-making.

## [Visualizing Disaster Tweets with Natural Language Processing](./NLP-DisasterTweets.ipynb)

This project utilizes pandas for data manipulation and analysis, matplotlib and seaborn for visualization, and nltk, spacy, and wordcloud for natural language processing. The goal is to visualize the most popular words and locations tweeted during a disaster.

# Big Data

## [Predicting Calgary Housing Prices](./predicting-calgary-housing-prices/)

This project focuses on predicting housing prices in Calgary, utilizing big data technologies such as PySpark for scalability. The team of five members processed data using resilient distributed datasets (RDD) and performed exploratory data analysis (EDA) and regression analysis with PySpark's MLlib.

The project involves three main categories of features: Economic Indicators, Group Price Indicators, and Individual Price Indicators, each contributing to understanding and predicting housing prices. Economic indicators include factors like average home price and unemployment rate, while group price indicators encompass community-based factors like crime rate and resident count. Individual price indicators focus on specific property characteristics like land size and dwelling type.

The team's presentations document the project's progress, including introductions, data preparation, EDA, modeling techniques, and results. The final report provides a comprehensive overview of data acquisition, processing, and modeling.

Data was sourced from various sources including The City of Calgary, Statistics Canada, and other relevant sources to ensure a robust analysis of housing price prediction in Calgary.

Overall, the project demonstrates a thorough approach to leveraging big data technologies for predicting housing prices, with a focus on scalability and accuracy.

## [Housing Permits](./housing-permits)

Using resilient distributed dataset (RDD) to pre-process and perform basic exploratory data analysis big data using PySpark and a Google Colab notebook.
