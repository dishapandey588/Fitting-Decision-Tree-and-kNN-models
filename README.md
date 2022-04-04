# Fitting-Decision-Tree-and-kNN-models

1.	Here, we write a python function that takes the predicted labels and the true label arrays, and computes the ROC curve as well as the area under the ROC curve/Area Under Curve(AUC). 
2.	Then we use the above function and matplotlib to draw ROC curves with varying thresholds and determine the best model in terms of the AUC.
3.	We repeat step 2 with the reference implementation from scikit-learn.
4.	Lastly, we fit suitable k-nn and decision tree models to the Weekly dataset (originally found in the ISLR package in R), and compare them with the best logistic regression model obtained in part 2. Report the confusion matrices, accuracies, AUCs and the ROC curves and comment on which model is the better one among the three types.
