# Sentiment Analysis using Techniques in 10-315 and Applications in Stock Prices

## Introduction:
For this final project, our team decided to create a machine learning model for sentiment analysis, which basically reads a sentence and determines whether it consists of a positive or a negative tone. The dataset we will be using is called [Stock-Market Sentiment Dataset](https://www.kaggle.com/datasets/yash612/stockmarket-sentiment-dataset), which consists of 2 columns, the text and whether it's positive or negative. Since these are taken from the stock market news, we are also able to apply our model to other news websites and predict their sentiment. Using this, we shall also analyze whether there is a strong correlation between the sentiment of the news as well as the change in price of a stock, which uses this [dataset](https://www.kaggle.com/datasets/BidecInnovations/stock-price-and-news-realted-to-it?select=AppleNewsStock.csv).

However, in order to 'elevate' our project, we decided to apply a lot of things we learned in 10-315. Hence, we have used the following techniques in creating our model:

- Decision Trees
- K-Nearest Neighbor
- Linear Regression
- Logistic Regression
- Neural Networks
- Regularization
- Naive Bayes
- Gaussian Distrimanant Analysis
- Principal Component Analysis
- Support Vector Machines

Within the scale of this project, our goal is to determine which model would be best for our classification, and whether a combination of these models would achieve a better result.

In the grand scheme of things, our goal is that for future students who might take the course, they could see how the basic theory learned in class can be directly used in projects like these in real life.

Credit to this article for inspiration: https://www.kaggle.com/code/darkcore/basic-nlp-classify

Note for TA's: For this project, we felt that a flag for train=false is not suitable, since our models are not pre-trained, they do not take that long to train, and it improves the user experience since they can train it themselves with little time! 
## Conclusion:
In the end, we determined that individually, a Support Vector Machine works best for such a classification task, which achieved an accuracy of 77%. Furthermore, a combination of all the models does not seem to have a huge difference for directly analyzing sentiment, and neither model does well in predicting stock prices. This is because a lot of factors influence the change in stock prices other than the news itself.

