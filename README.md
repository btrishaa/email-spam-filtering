# email-spam-filtering

https://github.com/btrishaa/email-spam-filtering.git

Developed a classification algorithm, to filter email spam, using the Naive-Bayes Algorithm. The dataset consisted of a corpus of 6K labeled emails; applied text analytics and language processing techniques to train the model.

Implemented a simple machine learning algorithm to classify emails (Spam or Not Spam aka Ham) using Scikit-learn by implementing a Spam filtering classifier based on Multinomial Naive Bayes Algorithm


## Prerequisites

* Machine Learning
* numpy (http://www.numpy.org/), a powerful N-dimensional array object
* Multinomial Naive Bayes Algorithm (https://monkeylearn.com/blog/practical-explanation-naive-bayes-classifier/)

Spam filtering problem is solved in three different sections
* Prepare the data
* Build the training data
* Train the classifier
* Test the classifier for its accuracy
* Classify a new email with our trained classifer

## Prepare the data

Download the publicly available Lingspam dataset (http://www.aueb.gr/users/ion/data/lingspam_public.tar.gz).
Use the `bare > part1` from the downloaded dataset as the trainig data and `bare > part2` as the test data. Create two new directories, rename them - train_data and test_data. Now copy all the files from `bare > part1` to train_data and copy some random files from `base > part2` to test_data.

### References
* https://monkeylearn.com/blog/practical-explanation-naive-bayes-classifier/
* https://appliedmachinelearning.wordpress.com/2017/01/23/email-spam-filter-python-scikit-learn/
* http://www.tutorialspoint.com/numpy/
* https://github.com/alameenkhader/spam_classifier/edit/master/README.md
