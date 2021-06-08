# Twitter-sentiment-analysis
Tweets from the account of Mr Bill Gates are extracted and sentimental analaysis is performed on them after text cleaning.

## Extracting information from Twitter:  
Extracting information from Twitter using Tweepy on which we need to perform Sentiment Analysis. Using the consumer keys and access keys we can extract the tweets from twitter. 
These consumer_key,consumer_secret,access_key, access_secret are generated using your own twitter api account with a request. Once these keys are generated, by using tweepy
and these keys we can extract tweets from twitter. Now store all the extracted tweets as a list. 

## Text Cleaning:  
Since we have got all text data in the form of a dataframe, now we will perform Text Cleaning on data such as    
- Removing all the http links from the tweets   
- Removing all the puntuations, numbers and lowering the case of  letters   
- Splitting the paragraph into words   
- Importing the stop words (given as text file)   
- Removing all the stop words (that are given) from the tweets   
- Joining all the tweet words into one paragraph 

## Sentiment Analysis:  Once we get all the data interms of paragraph:    
- Import the positive words   
- Import the negative words   
- Remove the words from paragraph which are not present in the positive words and join  remaining words as paragraph - These are positive tweets    
- Remove the words from paragraph which are not present in the negative words and join  remaining words as paragraph - These are negative tweets   
- Now build a wordcloud for positive tweets and wordcloud for negative tweets and can  find most frequent positive and negative words   
- For these tweets Most frequent positive words are "Love", "Happy", "beautiful","good", "work","fun", Most frequent negative words are "miss","damn","bad","missed"   
- Number of positive words are higher than neg words so we can say it as positive tweet.
