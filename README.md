# British-Airways-Data-Science-Project

British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world.

It is beneficial to understand customer's feelings, needs, and feedback so that it can be used for improving the customer experience. 

## Using NLP to generate insights from customers reviews

After scraping data from skytrax website, I have used three ways to generate insights-

1) Sentiment Analysis- Sentiment analysis (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative or neutral. *File : Sentiment Analysis & Word Cloud.ipynb*

2) Word Cloud- Word clouds represents word frequency in which greater prominence is given to words that appear more frequently in a source text. The larger the word in the visual the more common the word was in the document. *File : Sentiment Analysis & Word Cloud.ipynb*

3) Topic Modelling-  It falls under the category of unsupervised learning and works by representing a text document as a collection of topics (set of keywords) that best represent the prevalent contents of that document. *File : Topic Modelling.ipynb*

## Predictive Modelling to understand customer booking behaviour- 

We use predictive models to understand factors that influence buying behaviour. The data is attached in the data folder 'customer_booking.csv'. 

In this process we have first understood the data using **Exploratory Data Analysis** and preprocessed it to increase the data quality for effcient models. 

The model is able to predict completed bookings with a precision of 67% and incomplete bookings with a precision of 73%. It can be enhanced by using many other ML models such as Support Vector Machine or Gradient-boosted tree. 
