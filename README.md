# Credit_Risk_Analysis Overview:

###### Jill asked me to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. The LendingClub dataset will be used for various mechine learning credit risk models and their performance will be evealuated.  

# Results: 
###### The results are based on:
- Precision: the ability of a classifier not to label an instance positive that is actually negative.  For each class it is defined as the ratio of true positives to the sum of a true positive and false positives. The higher the precision the better.
- Recall: the ability of a classifier to find all positive instances. For each class it is defined as the ratio of true positives to the sum of true positives and false negatives.  The higher the recall, the better.
- F1: the mean of precision and recall such the best score is 1.0 and the worst is 0.0.

###### Below are the scores of each model.
- Deliverable 1
###### Naive Random Oversampling
![Naive Random Oversampling](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/%20Naive%20Random%20Oversampling.png)
###### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/SMOTE%20Oversampling.png)

- Deliverable 2
###### Cluster Centroid Undersample  
![Cluster Centroid Undersample](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/Cluster%20Centroid%20Undersample.png)
###### SMOTTENN Over/Under
![SMOTTENN Over/Under](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/SMOTEENN%20Over:Under.png)

- Deliverable 3
###### Balanced Random Forest Class
![Balanced Random Forest Class](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/Balanced%20Random%20Forest%20Classifier.png)
###### Easy Ensemble AdaBoost Class
![Easy Ensemble AdaBoost Class](https://github.com/ramon0101alonso/Credit_Risk_Analysis/blob/main/Pictures/Easy%20Ensemble%20AdaBoost%20Classifier.png)


# Summary: 
###### According to the results, the Ensemble Classifiers has the highest recall score and the SMOTEENN algorithm has the lowest.  All models precision low risk is 1.0 except for the naive random oversampling.  The Easy Ensemble AdaBoost Classifier has the highest f1 score of .97.  It seems that using the Ensemble Classifiers gives the best results to identify credit risk.