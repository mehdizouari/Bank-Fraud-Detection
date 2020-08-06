# Bank-Fraud-Detection
Using a credit card fraud detection dataset, we build a binary classification model that can identify transactions as either fraudulent or valid, based on provided, historical data
In a 2016 study, it was estimated that credit card fraud was responsible for over 20 billion dollars in loss, worldwide. Accurately detecting cases of fraud is an ongoing area of research.


Labeled Data
The payment fraud data set (Dal Pozzolo et al. 2015) was downloaded from Kaggle. This has features and labels for thousands of credit card transactions, each of which is labeled as fraudulent or valid. In this notebook, we'd like to train a model based on the features of these transactions so that we can predict risky or fraudulent transactions in the future.

Binary Classification
Since we have true labels to aim for, we'll take a supervised learning approach and train a binary classifier to sort data into one of our two transaction classes: fraudulent or valid. We'll train a model on training data and see how well it generalizes on some test data.

The notebook will be broken down into a few steps:

Loading and exploring the data
Splitting the data into train/test sets
Defining and training a LinearLearner, binary classifier
Making improvements on the model
Evaluating and comparing model test performance
