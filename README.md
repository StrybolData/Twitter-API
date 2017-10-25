# Flexibel Twitter Market sentiment analyser

The flexibel Twitter sentiment analyser, able to predict the sentiment of any given text, based on test dataset of 5000 tweets.
The tweets are created via an Tweeter API streaming connection.
The train dataset contains 5000 tweets and its own labelled keyword, based on an own created csv containing 500 rows of a keyword and a label(sentiment)
Eventually the ML model is defined by a Multinomial Bayes logarithm labeling every word in the tweet.
