# SMS Spam-Classifier

this is a SMS spam classifier project which can tell whether an sms is a spam or not with 97% accuracy.

I built this spam classifier model using a Support Vector Machine classifier.

The dataset used was taken from Kaggle.com (a link to which is meentioned in the .ipynb)
The dataset was split into a training and testing dataset by stratifying it on the basis of our target column because there was a big difference between the number of spams and number of hams.
The ratio was nearly the same in the training and testing dataset.


I used CountVectorizer for feature extraction of the text data(i.e., SMSs) with hyperparameters such as lowercase(which converts the text into a lowercase test) and stop_words(which, removes all the stop words from the text data)
The output was a sparse matrix.


Finally, after training the model on training set and calculating the scores, i get a really outstanding result on both, train as well as test dataset.
