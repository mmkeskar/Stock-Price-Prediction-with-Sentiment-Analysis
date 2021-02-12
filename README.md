# Stock Price Prediction with Sentiment Analysis

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is to be able to predict stock prices effectively using the market sentiment for the day and the LSTM predictions.
There seems to be a [correlation](https://github.com/mmkeskar/Stock-Analysis-with-NLP) in the market sentiment for a particular day that is calculated based on the twitter comments collected everyday pertaining to the companies whose stocks we are considering (Facebook, Apple, Amazon, Netflix, Google, and Tesla). This means that the difference in the LSTM and ARMIA predictions can be expalined by the sentiment calculated from the twitter comments. This project aims to verify those findings.


### Methods Used
* Machine Learning
* Data Visualization
* Predictive Modeling


### Technologies
* Python
* Tableau
* Pandas, jupyter, NumPy, TensorFlow, SpaCy, sklearn

## Project Description
In our [previous project](https://github.com/mmkeskar/Stock-Analysis-with-NLP), we showed that the difference in the ARMIA predictions and the actual stock prices for the FAANG comapanies like Facebook, Apple, Amazon, Netflix, Google, and Tesla (out of personal interest) can be explained by the daily market sentiment. 

In this project, we used two different sets of data, twitter comments and reddit comments, to calculate two separate market sentiments on each of the datasets. We also used the  LSTM model instead of ARMIA to make our stock price predictions. The model trained on the twitter data was retrained on reddit data to achieve about 75% accuracy on the reddit comments. This model was used to predict the sentiment for each comment collected for a particular day. Then a variety of metrics are used to calculate the market sentiment based on all the predicted sentiments for that day. Then, we used a Linear Regression (OLS Regression) to predict the stock price based on this calculated daily sentiment and the LSTM predictions. 

These results are then visualized.
This verifies that the missing information or the gap in the LSTM predictions and the actual stock prices can be explained by the daily sentiment captured for that day. We also compare the effect of changing the dataset for the sentiments, twitter and reddit. We also analyse which of the two: twitter and reddit, perform better on to make stcok price predictions.


## Needs of this project

- Data Collection 
- Data Cleaning and Preprocessing
- Machine Learning
- Data Visualization
- writeup/reporting


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing DSWG Members

**Team Lead (Contacts) : [Maitrayee Keskar](https://github.com/mmkeskar)(@slackHandle)**

#### Other Members:

|Name     |  Slack Handle   | 
|---------|-----------------|
|[Xuewei Yan](https://github.com/[github handle])| @johnDoe        |
|[Rishabh Viswanathan](https://github.com/[github handle]) |     @janeDoe    |
|[Kevin Jay](https://github.com/[github handle]) |     @janeDoe    |
