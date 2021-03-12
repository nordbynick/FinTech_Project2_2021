# FinTech_Project2_2021
Kedar, Alex, Nick

**START INITIAL OUTLINE**

Project Name: Boom or Bust
What are we trying to do?
Trying to predict bankruptcies
 
How?
Using NLP &, time permitting, other factors (reference 14.3.2 Austin Coffee Shop for the easiest initial NLP method & 12.2.6 for vader sentiment)
We will identify 10 companies that have gone bankrupt (different industries) & add them to our data frame
We will identify 10 companies (corresponding by industry to above companies) that are in good health & then add them to our data frame
We will use the above data set to train our model
 
Data
To start: 3 columns
Company name
Column containing either article or words (we can manually copy/paste information into a data frame, or we can pull recent articles from a source like Reuters)(we want to focus the articles or text on a time period that is at least within 1 year of the bankruptcy)
Column with binary classification "1" for Not Bankrupt, and "0" for Bankrupt
Easiest way to pull initial data is to either build the data frame manually and use relevant articles & copy/paste… or more dynamically, we can use the Reuters library to pull in info from a specific timeframe… or we can look into a new news source that may suite us well
Stretch: We add more columns with different data to include in training our model (such as assets, liabilities, etc.)
 
Model:
We will train our model on the data mentioned above
 
Testing our model:
We will test our model on 2 companies that are currently in good health, 2 companies we know have gone bankrupt but we did not train data on, and 2 companies that are on the brink of bankruptcy. We will use the outcomes to gauge the accuracy of our model
 
Stretch:
We will include more companies in our dataset
We will include more columns for data and on which to train our model 

**END INITIAL OUTLINE**
