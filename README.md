# FinTech_Project2_2021
Kedar, Alex, Nick

Project Name: Boom or Bust

**NOTE TO PROJECT RESTRUCTURE**: When we initially set out to do our project, we wanted to use NLP data to predict bankruptcies. We used the first two classes devising our approach, models, outlines, etc; however, once we started writing the code we ran into several major issues. First, while resources like newsapi and aylien did offer powerful news api's, to have access to news lookbacks greater than several months cost large amounts of money or required corporate accounts (also expensive). Given we needed data going years back (we were looking at 2020 bankruptcies and needed 2019 NLP data), we were in a conundrum. As such, we needed to restructure our project to fit within the constraints of our tools. The major constraint was the 1-month news/information lookback for newsapi.org. With this constraint we decided to update our project to use 1-month NLP data to predict if a stock price would go up or down over the course of a month. We would then use the ML models learned in class to draw conclusions.

What are we trying to do (update)?

> Use one month of NLP data & one month of stock price data, for a select group of companies, to train a model to predict stock prices
 
 
How (update)?

> Using 1-month NLP data from newsapi.org & other relevent stock factors from our Fidelity.com screener/excel export
> We will use the above data set to scale, train, and test a model
> We will evaluate a number of different ML models to determine the best fit
 
 
Data (update): 

> 1) Company name & ticker

> 2) Column containing either article or words (we can manually copy/paste information into a data frame, or we can pull recent articles from a source like Reuters)(we want to  focus the articles or text on a time period that is at least within 1 year of the bankruptcy)

> 3) Column with binary classification "1" for Not Bankrupt, and "0" for Bankrupt
Easiest way to pull initial data is to either build the data frame manually and use relevant articles & copy/paste… or more dynamically, we can use the Reuters library to pull in info from a specific timeframe… or we can look into a new news source that may suite us well
Stretch: We add more columns with different data to include in training our model (such as assets, liabilities, etc.)
 
 
Model:

> We will train our model on the data mentioned above
 
 
Testing our model:

> We will test our model on 2 companies that are currently in good health, 2 companies we know have gone bankrupt but we did not train data on, and 2 companies that are on the brink of bankruptcy. We will use the outcomes to gauge the accuracy of our model
 
 
Stretch:

> We will include more companies in our dataset

> We will include more columns for data and on which to train our model 


Resoureces:
https://fortune.com/2020/06/29/companies-filing-bankruptcy-2020-during-coronavirus-pandemic-covid-19-economy-industries/


Likely Libraries & APIs:

> newsapi

> sklearn

> tensorflow

> nltk.sentiment.vader


Tasks:

> Begin building out the Data Set (Kedar has started)

> Begin building python file

> TBD

**END INITIAL OUTLINE**
