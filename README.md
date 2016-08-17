# Twords

Twitter Word Frequency Analysis

Twords takes in a csv file of tweets (gathered using GetOldTweets here: https://github.com/Jefferson-Henrique/GetOldTweets-java), 
cleans them, removes stopwords, and visualizes the frequency of words (including frequencies relative to background word frequencies drawn from a sample of tweets from the Twitter API). 

It also lets you add your own stop words and query specific words or groups of words for their relative frequencies. 

Code now includes a separate sentiment class for returning the sentiment of the tweets as measured by Stanford CoreNLP code.

To do: add example comparing sentiment time series with stock price time series. Stock prices can be downloaded automatically with pandas. 

Also to do: get sentiment information from collection of background tweets in same time period. 

