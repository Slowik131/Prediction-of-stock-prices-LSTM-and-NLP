
# Abstract
I used neural network and machine learning  to evaluate past data concerning the stock market, as well as news titles of the corresponding time period to make predictions about stock market trends. Ii built a model that predicts whether the next day prices of stocks would go up or down. I used a variety of techniques while building the model, such as natural language processing, sentiment analysis and text mining.

## Introduction
Natural Language Processing is a technique used by a computer to understand and manipulate natural languages. By natural languages, I mean all human derived languages. Natural language processing or NLP for short is used to analyze text and let machines derive meaning from the input. This human-computer interaction allows us to come up with many different applications to bring man and machine as one. In our project,  I use NLP techniques to evaluate stock data from the news titles from in order to make predictions in stock trends.

In order to proceed with this objective, I needed to understand what Sentimental Analysis is. Sentimental Analysis is an analytical method that the computer uses to understand a natural language and deduce if the message is positive, neutral or negative. In our case, Sentimental analysis refers to the deduction of the news headlines if they increase the stock or reduce it. By doing so, we end up with the ‘emotional’ status of the data which is what sentimental analysis gives its user.

## Data Collection
I scraped data concerning the stock market from Yahoo Finance and news titles were taken from reuters news titles dataset. 

## Workflow
In a file called Sentiment, I worked on sentiment analysis of news titles from three chosen companies. Apart from preprocessing data, i.e. deleting not needed columns, I created a sentiment analyzer, which gave us a numeric value corresponding to a given sentiment. I then created models for three separate companies - Apple, Microsoft and Boeing in order to predict the stock market trends. In each of the three files concerning the chosen companies, I firstly scraped needed data, applied sentiment analyzer and finally built some models. In each file, I created a couple of different models, i.e. a regular Sequential model, models using LSTM and GRU, as well as a model using no sentiment analysis, in order to find the most accurate solution.

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


