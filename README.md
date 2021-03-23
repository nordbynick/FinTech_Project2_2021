# FinTech_Project2_2021

Kedar, Alex, Nick

Project Name: Boom or Bust

Attachments:

> BOOMorBUST = python file
 
> monthly_modeling_df = our csv with final data used 

**NOTE TO PROJECT RESTRUCTURE**: When we initially set out to do our project, we wanted to use NLP data & sentiment to see if we could predict bankruptcies. We used the first two classes devising our approach, models, outlines, etc; however, once we started writing the code we ran into several major issues. The biggest issue was that while resources like newsapi and aylien did offer powerful news api's, having access to news lookback periods greater than several months cost large amounts of money or required corporate accounts (also expensive). Given we needed data going several years back (we were looking at 2020 bankruptcies and needed 2019 NLP data), we were in a conundrum. As such, we needed to restructure our project to fit within the constraints of our tools. The major constraint was the 1-month news/information lookback for newsapi.org. With this constraint we decided to update our project to use 1-month NLP data to predict if a stock price would go up or down over the course of a month. We then used the ML models learned in class to draw conclusions.

What are we trying to do (update)?

> Use one month of NLP data & one month of stock price data to train a model to predict stock prices
 
 
How (update)?

> Using 1-month NLP data from newsapi.org & other relevent stock factors from our Fidelity.com screener/excel export
> We will use the above data set to scale, train, and test a model
> We will evaluate a number of different ML models to determine the best fit
 
 
Data (update): 

> 1) Company name & ticker

> 2) Column or columns containing positive/negative/neutral/compound NLP sentiment

> 3) Column with binary classification "1" for stocks that went up, and "0" for stocks that went down

 
Training & Testing Our Model (update):

> We will tryi a variety of ML models, focused around classifaction models & models that evaluate binary outcomes (did the stock go up or down, and how are these movements correlated to NLP data & sentiment)
 
 
Stretch:

> We will include more identifying factors in our dataset (financial data, market data, macro economic data)


Resoureces:

> Fidelity.com

> Newsapi.org


Likely Libraries & APIs:

> newsapi

> sklearn

> tensorflow

> nltk.sentiment.vader


Tasks:

> Search for best stock data (Kedar)

> Build NLP function (Nick)

> Run models (Alex) 


Findings:

> Please reference out slide show pdf attached
