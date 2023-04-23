# Module-18---Credit-Risk-

##Overview of the Project 
Jill has asked us to use imbalanced-learn and scikit-learn to build models to evaluate the real world challenge of assesing credit risk. Using data from Lending Club we will oversample the data (RandomOverSampler & SMOTE) and undersample the data with (ClusterCentroids, then combine these approaches with SMOTEENN. Then we will use two machine learning models used to reduce bias: BalancedRandomForestClassifier and EasyEnsembleClassifer to help predict credit risk. Once this is complete we will write up a reccomendation on whether these models should be used to predict risk.

###Results 

###Summary 
For all models tested, utlizing EasyEnsembleClassifier provides the highest score for all risk loans. The precision is low for all the models. Above the 90% of the current analysis, utlizing EasyEnsembleClassifier can perform a High-Risk loan precision as a value for the analysis.
