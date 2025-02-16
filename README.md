# ENSEMBLING FOR STATISTICAL ARBITRAGE IN CRYPTOCURRENCY MARKETS
- In this project, we propose an ensemble algorithm comprising of three machine learning models: logistic regression, random forest and long short-term memory (LSTM) networks. Logistic regression facilitates baseline predictions, random forest enhances model stability through ensemble predictions (being part of the ensemble models family), and LSTM networks address sequential dependencies in price movements. Combining their outputs, the ensemble aims to increase predictive accuracy of the overall result.

- More specifically, we aim to train all the three models on the lagged returns of 30 cryptocurrency coins with the objective of predicting whether the coin will outperform the overall cross-sectional median of the overall coins in the next 2 hours. After training, the predictions from the three models will be ensembled to give a more accurate prediction value that will be used to rank the coins by performance in a descending order. We go long for the top 3 and short the flop 3 and reverse our positions after the two-hour period. We then evaluate the approach on the out of sample historical data and compare the results with the baseline strategies under consideration.

## Technical Tools Used
Several python libraries have been used in this project since the entire project was implemented mainly using the python programming language. These libraries include:
* **Pandas** for reading in data and data manipulation purposes
* **Numpy**  for simple mathematical operations
* **Seaborn and matplotlib** for data visualizations
* **Scikitlearn** for data preprocessing, model training and evaluation

All the libraries mentioned above are open source and readily available from their respective online sources.

**Flask framework** was also used in deploying the models for use with the non technical persons.


The proposed approach will be a robust application of statistical arbitrage within the cryptocurrency space. However, since the strategy relies on historical data, it might not be guaranteed to perform in a similar manner under future prevailing market conditions.

## Licensing
This project is stricly for academic purposes and as such should not be reproduced without the consent of all the contributors.

