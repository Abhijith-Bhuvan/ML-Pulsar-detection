# Plusar-Detection

This project was for a course on artificial inteligence at IISER Bhopal.
Extract the data.rar into the same folder as the .ipynb file.

The following abstract is from the Minimal Feature Pulsar classification using Machine learning.docx file.

The objective of this project is to create a classifier that can read the data files of stars and predict 
whether they are pulsars or not with acceptable errors using the least amount of features. 
For this, an AdaBoost classifier was used. AdaBoost is an ensemble learning method created to 
increase the efficiency of binary classifiers. It uses an iterative approach to learn from the mistakes 
of weak classifiers, and turn them into strong ones. 
For features, Log of the signal-to-noise ratio and Skew of the folded proﬁle were used. 
•  SNR is a measure of the purity of the signal. 
•  The pulse profile of the star can be folded and it’s skew can be calculated to give a numerical 
measure of the radio pulse profile. 
Even on a dataset of only 2392 stars, of which only half are pulsars, the classifier is able to obtain a 
recall rate of 97.7% with a low False Positive Rate of 2.7%.
