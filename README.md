# airline_tweet_nlp
In this project, we aim to understand customer complaints on social media, specifically Twitter, regarding the major airlines in the US.

## Objective
The objective of the project is using twitter post to derive negative aspects that people are likely to mention when talking with their experience with airlines and recommend possible solutions.

## Dataset
The data originally came from Crowdflower's Data for Everyone library, which was then made available to us on Kaggle. The twitter data was scraped from February 2015 for 2 weeks. It contains over 14K tweets and their sentiment (positive, neutral, or negative) regarding 6 major airlines in the US. [data link here](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)

## Approach
We compared 4 different algorithm (Random Forest, Recurrent Neural Net, Logistic Regression, and Multinomial Naive Bayes) to identify the sentiment in the tweets, including positive, negative, and neutral.
Additionally, we built an LDA model to identify the topics within the negative tweets.
