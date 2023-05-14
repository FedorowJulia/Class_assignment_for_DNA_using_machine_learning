Introduction:
This script performs analysis on the genetic sequences of humans, dogs, and chimpanzees. It generates k-mers (substrings of length k) from the sequences, and trains a Naive Bayes classifier on the k-mer features to predict the family class labels of the sequences.

Gane family and its class label:
G protein coupled receptors – 0
Tyrosine kinase – 1
Tyrosine phosphatase – 2
Synthetase – 3
Synthase – 4
Ion channel – 5
Transcription factor – 6

Steps:
The script performs the following steps:
Import necessary libraries.
Read data from files.
Perform exploratory data analysis, including checking the distribution of class labels and removing sequences that contain the letter "N".
Define a function to generate k-mers from sequences.
Find the best value of k for generating k-mers by training and evaluating a Naive Bayes classifier on the k-mer features.
Refit the model with the best value of k and make predictions on the test set.

Results
The script outputs performance metrics for the Naive Bayes classifier (accuracy, precision, recall, and F1 score) for each value of k tested. It also outputs the best value of k and the corresponding performance metrics.
