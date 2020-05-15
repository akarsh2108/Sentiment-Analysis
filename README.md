# Sentiment-Analysis
Sentiment Analysis is done using Naive Bayes Classifier. Here, every sentence contain either a positive sentiment represented by 1 or a negative sentiment represented by 0. 

Now, for a test sentence probability of it occuring in both the classes is calculated using Bayes Theorem. The class which gives maximum probability will be the predicted sentiment for that corresponding sentence. 

Laplace Smoothing is also applied here to account for a zero probability.

Results - 
The Dataset is split into train and test in a 80:20 ratio, after which another split is made from the training set dividing it into 5 equal parts, in which 4 parts used as training set and 1 part used as validation set.
K-Fold Cross Validation is applied here with k=5. Validation Accuracy obtained on all the k-folds is ~ 80 +/- 2 %. Accuracy obtained on the test dataset is roughly around 82%.
