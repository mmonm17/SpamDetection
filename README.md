# SpamDetection
This project was done for our Intro to Machine Learning Class (CSINTSY).  The project aims to train machine learning models to classify messages as either 'ham' or 'spam.'

The dataset used for this project was taken from: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

Various pre-processing methods were done prior to training, including cleaning, noise reduction, and lowercasing. One set of models was preprocessed with the removal of stop words, which performed worse than the models where stop words were not removed.

Afterward, a Bag-of-Words model and TF-IDF model were created and were each trained using the Naive Bayes and Logistic Regression algorithms. 

The trained models were tested and compared, and the F1 score was used as the main performance metric.

Further details can be seen in the paper attached.
