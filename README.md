# AI-fraud-detection-algorithm

An artifical intelligence algorithm developed to detect fraudulent credit card transaction, dataset as proposed on Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud.

# Context
Anomaly analysis has extension real world use, and can assist in the prevention of an event much before it's to cause any substantial or degrading effect. Its' applications span from malignant tumour detection in MRI scans in the Medical sciences, to tectonic seismic activiy in Geology, and more.

# Motivation
We will use a recurrent neural network trained over 10 epoches and will balance the labelled class so that we have an equal number of fraudulent and non-fraudulent transaction for our model to train on without developping a bias to the initially majority class.

# Final
To acheive an average accuracy measure of 99.97% is very appealing. It means it will only incorrectly cateogrise 9 transactions out of 30,000. If those 9 transactions were incorrectly identified as fradulent, then at worst it would be a false alarm! It's worth mentioning however that our initial dataset only had 0.172% of fraudulent transactions, with the remaining circa 99.818% being non-fraudulent meaning that an algorithm that classified all the transactions as non-fraudulent without dataset balancing would quickly overfit, having an accuracy of 99.82%, but a poor confusion matrix metric, the latter of which may be enough to bypass the uninitiated if further analysis is not applied to the model.
