
Use a classifier that is reliable to predict probabilities

Use the ROC Area Under Curve as score for optimisation

Try several thresholds to see the behavior of precision, recall and f1-score

Try a few selected threshold

The solution has a little change with respect to the version proposed in class:

- the scaler tries several scalers and tries also the no-scaling option (passthrough); nevertheless, with this specific dataset the StandardScaler turns out to be the best one