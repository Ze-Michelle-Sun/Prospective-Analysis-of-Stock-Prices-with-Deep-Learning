# Prospective-Analysis-of-Stock-Prices-with-Deep-Learning
## Main Goal
The proposed capstone project aims to develop a hybrid deep learning model for prospective analysis of stock prices, leveraging the power of deep learning models to make accurate predictions of future stock prices.
## Methodology
To achieve this goal, used a combination of three deep learning models. Firstly, utilized a Neural Network-based Regressor model to incorporate the impact of other companies on the target company. Secondly, used a Recurrent Neural Network (RNN) model to analyze the target company's past behavior and make predictions, accordingly, utilizing an LSTM layer. Lastly, an Artificial Neural Network (ANN) was used to combine the predictions of the other models to reach a firm and robust conclusion.
## Data Collection
- Scraped a Wikipedia page that contained a list of companies included in the S&P 500 index. This index measures the performance of 500 large companies listed on stock exchanges in the United States and is regularly updated, making it a reliable source of information.
- used the Yahoo Finance API to randomly gather daily data for 200 companies. The data covers the period from January 2015 to March 2023 and was extracted into separate CSV files for each company. 
## Data Preparation
- Data Preparation for Regressor Model
- Data Preparation and Feature Selection for RNN model
- Data Preparation for ANN Model
## Model Planning and Building
- Neural Network-based Regressor Model
- Recurrent Neural Network Model
- Artificial Neural Network
## Conclusion
The project demonstrates the potential of hybrid models in improving the accuracy of stock price prediction. While there is always room for improvement, the results suggest that a combination of machine learning models can provide more reliable predictions than any single model alone.
