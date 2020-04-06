# Spam-Classifier
Spam Classifier Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'.  In this mission we will be using the Naive Bayes algorithm to create a model that can classify dataset SMS messages as spam or not spam, based on the training we give to the model. It is important to have some level of intuition as to what a spammy text message might look like. Usually they have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!  Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

Here I have implemented preprocessing steps such as tokenizing, bag of words and also implemented Naive Bayes from scratch. Then I trained my preprocessed data on scikit-learn implementation of naive bayes and got evaluation scores as follows:

Accuracy score:  0.9885139985642498

Precision score:  0.9720670391061452

Recall score:  0.9405405405405406

F1 score:  0.9560439560439562
https://predictspam.herokuapp.com/
