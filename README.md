# Hashtag-Prediction
## Description:
This project uses NLP models to classify tweets as one of the following four hashtags: #crpyto, #thanksgiving, #lockdown, and #dogs. About 160,000 tweets from these four hashtags were collected. After filtering out tweets that were retweets, quoted tweets, or non-English tweets, about 45,000 tweets were left. In order to predict what hashtag a tweet belonged to various models were created, including two baseline models (logisitic regression and Naive Bayes), as well as neural network models which involved different word embeddings and structures. To evaluate the models, F1 scores were computed, in addition to other measurements and figures which can be found in the report and code.

## Files:

Statistical Software Final Report.pdf - A report of the project

all_tweets.csv - A collection of 44,746 filtered tweets with the first token of each line corresponding to the tweet's actual hashtag

Stat Software Tweet Collection.ipynb - notebook to collect tweets

Stat Software Tweet Cleaning.ipynb - notebook to clean and filter tweets

Stat Software Tweet Model Building - notebook to build all models and evaluate their accuracy
