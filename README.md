
# Abstract
We used neural network and machine learning  to evaluate past data concerning the stock market, as well as news titles of the corresponding time period to make predictions about stock market trends. We built a model that predicts whether the next day prices of stocks would go up or down. We used a variety of techniques while building the model, such as natural language processing, sentiment analysis or text mining.

## Introduction
Natural Language Processing is a technique used by a computer to understand and manipulate natural languages. By natural languages, we mean all human derived languages. Natural language processing or NLP for short is used to analyze text and let machines derive meaning from the input. This human-computer interaction allows us to come up with many different applications to bring man and machine as one. In our project,  we use NLP techniques to evaluate stock data from the news titles from in order to make predictions in stock trends.

In order to proceed with this objective, we needed to understand what Sentimental Analysis is. Sentimental Analysis is an analytical method that the computer uses to understand a natural language and deduce if the message is positive, neutral or negative. In our case, Sentimental analysis refers to the deduction of the news headlines if they increase the stock or reduce it. By doing so, we end up with the ‘emotional’ status of the data which is what sentimental analysis gives its user.

## Data Collection
We scraped data concerning the stock market from Yahoo Finance and news titles were taken from reuters news titles dataset. 

## Workflow
In a file called Sentiment, we worked on sentiment analysis of news titles from three chosen companies. Apart from preprocessing data, i.e. deleting not needed columns, we created a sentiment analyzer, which gave us a numeric value corresponding to a given sentiment. We then created models for three separate companies - Apple, Microsoft and Boeing in order to predict the stock market trends. In each of the three files concerning the chosen companies, we firstly scraped needed data, applied sentiment analyzer and finally built some models. In each file, we created a couple of different models, i.e. a regular Sequential model, models using LSTM and GRU, as well as a model using no sentiment analysis, in order to find the most accurate solution.

## Environment
We used Jupyter Notebook as well as Google Collab to work together and see what changes have been made.

## Conclusion
As we can see below from accuracy scores, sentiment definitely has impact on predicting stock prices trends, however not in every case. Depending on the company, the sentiment can be a very good feature for predicting future trends

### Apple
Without sentiment 

![image](https://user-images.githubusercontent.com/58428501/80479889-06a3ab80-8950-11ea-9e0c-4c828f94bbda.png)

With sentiment 

![image](https://user-images.githubusercontent.com/58428501/80367788-f6c29380-888b-11ea-9c2d-d581f2618bf7.png)

### Boeing
Without sentiment

![image](https://user-images.githubusercontent.com/58428501/80367902-28d3f580-888c-11ea-9482-5ed60e062905.png)

With sentiment

![image](https://user-images.githubusercontent.com/58428501/80367951-3b4e2f00-888c-11ea-9451-da70644492c6.png)

### Microsoft
Without sentiment

![image](https://user-images.githubusercontent.com/58428501/80368025-5c168480-888c-11ea-9bcc-63f1814e1a39.png)

With sentiment

![image](https://user-images.githubusercontent.com/58428501/80368057-6afd3700-888c-11ea-9e01-ab68cbf64121.png)


This project was definitely an eye-opening experience for us. Not only did it educate us in terms of using NLP and creating more complex models, but it also made us research and take interest in the stock market. We put a lot of work to make stock predictions as much accurate as they can be. We also got to know correlations between news titles and stock prices, which were sometimes very intriguing for us.

During the making of our project, we naturally encountered some difficulties, which were hard to overcome. We had to not only do extensive research and troubleshoot for a lot of hours, but also had to contact our professor, as we needed some expertise. We put a lot of effort to choose the most suitable layers and to train the best model, which also was not so easy to do.
