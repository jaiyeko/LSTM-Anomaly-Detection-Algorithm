# AI-fraud-detection-algorithm

A simple recurrent neural network developed to detect fraudulent credit card transaction from a sample dataset on Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud.

# Context
Anomaly detection has extensive real world application, and can assist Analysts in the prevention of an event before any substantial or degrading effect has occurred. Its' well documented applications span from malignant tumour detection in MRI scans in the Medical sciences, to tectonic seismic activiy in Geology, and more. Supervised anomaly detection techniques require a data set that has been labeled as "normal" and "abnormal" and involves training a classifier (the key difference to many other statistical classification problems is the inherent unbalanced nature of outlier detection).

# Motivation
Anomalies occur infrequently in datasets but it's crucial for our algorithm to correctly identify the ones that there are. SMOTE techniques can help in the analysis to bump the minority class to an extent that there are equal numbers of distinct labels. We will train the algorithm over 10 epochs and score validation accuracy.
