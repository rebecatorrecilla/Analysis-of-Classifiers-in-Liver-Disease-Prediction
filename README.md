# Analysis of Classifiers for the Detection of Liver Diseases in the ILPD Dataset
This work addresses the problem of classifying patients with liver disease based on the Indian Liver Patient (ILPD) dataset, presented as a competition on the Kaggle InClass platform.

The main challenge of this dataset is the strong imbalance between classes (sick and healthy patients). To solve this, a complete pipeline has been implemented that includes exploratory data analysis (EDA), feature engineering to reduce multicollinearity, and robust preprocessing with logarithmic transformation feature engineering to reduce multicollinearity, and scaling using RobustScaler to minimize the effect of outliers. The imbalance was managed using the SMOTE oversampling technique. 

Various models were evaluated, including Logistic Regression, Extra Trees, Random Forest, SVC, KNN, and ensembles such as VotingClassifier and StackingClassifier. Finally, the ExtraTreesClassifier, with an optimization of the decision boundary, proved to be the most effective model, achieving an F1-score (macro) of 0.7062 in validation, which translates into a competitive result in the public test of 0.6666 and good detection of healthy and sick patients.

