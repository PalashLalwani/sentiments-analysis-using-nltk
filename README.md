# sentiments-analysis-using-nltk

for this model nltk and scikit-learn is used for classification, which can give accuracy upto 73%. 

To reduce the time in training the data, the data is pick;ed once and saved in the pickleDtaset folder(by using pickleScript.py) such that we can run sentiment_mod.py by just using pretrained data in the pickle file.

sentiment analysis is performed on twitter data which is collected by tweepy api by generating keys from the twitter account.

Live sentiments are analysed by plotting graph using matplotlib.


This model is only for learning and implementing nltk. We can directly use TextBlob in python to directly generate the sentiments. This code is available in my previous repository:
 https://github.com/PalashLalwani/twitter-sentiment-analysis
