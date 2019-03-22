# Twitter-Sentiment-Analysis

In this project, I analyzed tweets for their sentiments using NLP and Machine Learning algorithms. For the tweets, I used the Twitter's Tweepy API which allows us to get live stream of tweets. (You'll of course need a developer account for that and will have to use you API keys.). 

I have uploaded the training and testing data which are positive and negative movie reviews. I trained the machine learning models on the most common words in the dataset which help in determining if the tweet is positive or negative. 

I trained 7 models in the data and then defined a Vote Classifier to collect votes from all the classifiers which improves the reliability of the prediction. After training each model once, they can be pickled so that they don't have to be trained again and again because it takes some time. 

Finally, I graphed the results using Matplotlib. 
