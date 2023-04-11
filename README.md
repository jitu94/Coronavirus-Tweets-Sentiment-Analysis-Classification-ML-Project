# Coronavirus-Tweets-Sentiment-Analysis-Classification-ML-Project
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then
Problem Statement
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then.The names and usernames have been given codes to avoid any privacy concerns.
We are given the following information:
1. Location
2. TweetAt
3. Original Tweet
4. Sentiment
5. User Name
6. Screen Name 
Variables Description
Answer Here

UserName: This column contains the username of the person who posted the tweet.

ScreenName: This column contains the screen name or handle of the user who posted the tweet.

Location: This column contains the location of the user who posted the tweet. This could be their city, state, country, or any other geographic location that they have specified in their Twitter profile.

TweetAt: This column contains the date and time when the tweet was posted.

OriginalTweet: This column contains the actual text of the tweet that was posted.

Sentiment: This column contains the sentiment label assigned to the tweet. This label could be positive, negative,extremely positive,extremely negative neutral, depending on the sentiment analysis algorithm used to classify the tweet.

Conclusion 


1.We applied 8 models namely, Logistic Regression with Grid Search CV, Decision Tree Classifier,Stochastic Gradient Descent , KNN, SVM,Multinomial Navies Bayes,Bernoulli Navies Bayes Classifier for both Count Vector And TF ID Vectorization techniques.

2..We conclude that the machine is generating the best results for the Stochastic Gradient Descent(count vectorizer) model with an Accuracy of 80.43% followed by the Logistic Regression with Grid Search CV (TF/ID vectorizer) model with an Accuracy of 78.86%.

3.In the future ,we can repeat the analysis and compare it with the present sentimental analysis to gauge the impact of the initiatives on the ground.
