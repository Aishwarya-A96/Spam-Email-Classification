Spam-Email-Classification using Naive Bayes classification
This dataset contains subject of emails and a classification label whether the email is a spam or ham
Spam is represented as 1 and good email also known as ham is represented as 0
Dataset shape: 5728*2
Spam Email Percentage was found to be 23.88%
Ham Email Percentage was found to be 76.12%
I used CountVectorizer to text column and converted the words to zeros and ones
I fitted the model using Naive Bayes classifier
I gave sample text to test whether it classifies correctly as spam or ham and it classified correct
I splitted the dataset into trainset and testset and fitted the model
xtrain shape:4296**37303
ytrain shape:4296
xtest shape:1432*37303
ytest shape:1432
Among 4296 xtrain samples 15 were were predicted as ham but they are actually spam and 1 was predicted spam but they are actually ham and accuracy was found to be 99.62%
Among 1432 xtest samples 7 were predicted as ham but they were actually spam and 5 were predicted as spam but they were actually ham and accuracy was found to be 99.16%
