# ArticlePriority
using twitter trending hashtags to find if keywords from our articles are relevant or not
the function is simple and returns 1 or 0 based on relevance and can be easily modded for better scaling

TF-IDF to identify keywords

A python notebook following a tutorial on how to use TF-IDF to comb through a bunch of articles to generate a set of general words. And then save the generated feature-names, TF IDF transformer and the count vectorizer to a pickle file
Tutorial followed : https://www.freecodecamp.org/news/how-to-extract-keywords-from-text-with-tf-idf-and-pythons-scikit-learn-b2a0f3d7e667/

Tweepy

Using the twitter API we can get the trending hashtags of a particular location using its WOEID
A file containing twitter recognised woeid's can be found here: https://gist.github.com/edsu/a5f6c1188ec3a27d38634721fb25fffb
Configure the twitterApiConfig.ini file to fit your input tokens and you are good to go
