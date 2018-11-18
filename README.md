# SPAM Classifier

An application to distinguish spam from other mails using Machine Learning Techniques.

An application to distinguish spam from other mails using Machine Learning Techniques.  We use scikit library and python numpy library for this project.  Here the dataset is taken from uci dataset for spam.  We vectorize the text body by embedding the words – 'hello','how','are','you' in the form of a one hot encoding. 
We split the data in the ratio of 90:10 for train and testing.  We apply different machine learning classification algorithms like KNN, Naive Bayes, SVM and Random Forest Algorithms. We find that Random Forest algorithm has the best accuracy for the given test set. 

To tune the hyperparameters, we use GridSearchCV option from the scikit library. 


