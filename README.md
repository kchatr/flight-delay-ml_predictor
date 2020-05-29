# flight-delay-ml_predictor

This is a program which uses machine learning on a binary classifier to determine the probability that a specific flight will be delayed. The model accounts for the features: Origin Airport; Destination Airport; Expected Time of Departure; Expected Time of Arrival. 

The model itself is trained on a large database containing thousands of entries from airports within the United States - this, sadly, means the model can only work for arrivals and departures at the following airports: ATL, DTW, JFK, MSP, and SEA.

It uses a random forest classifier from SciKit Learn in order to analyse and classify the data, as well as using a confusion matrix and an AUC-ROC curve to show the accuracy and precision of the model. 
