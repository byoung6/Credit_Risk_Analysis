### Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The exercise is to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. We also use the credit card credit dataset from LendingClub, a peer-to-peer lending services company to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We then use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

- Naive Random Oversampling

![Naive Random](https://user-images.githubusercontent.com/76926631/153775682-118a6113-5468-4eba-a10f-d4931e446098.PNG)


- SMOTE Oversampling

![SMOTE](https://user-images.githubusercontent.com/76926631/153775679-6744568c-7013-4ec1-93bf-0920232bb83f.PNG)


- ClusterCentroids 

![Undersampling](https://user-images.githubusercontent.com/76926631/153775669-0f2aa153-ef3e-4129-98dc-888a99491c8a.PNG)


- Combination (Over and Under) Sampling Through Counter

![imbalanced](https://user-images.githubusercontent.com/76926631/153775662-42506871-3154-4c88-828a-f17f714b8adb.PNG)


- Balanced Random Forest Classifier

![BRFC](https://user-images.githubusercontent.com/76926631/153775656-7361f63e-99e6-443c-af76-2786ebdacfcf.PNG)

- Easy Ensemble AdaBoost Classifier

![EEA](https://user-images.githubusercontent.com/76926631/153775650-17bd7bb3-6f6d-4c82-af83-396510448c41.PNG)

## Summary

All models show a low precision score for high-risk loan applicants, and a high precision score for low-risk loan applicants. All six models show approximately 1-7% precision rating for determining high-risk applicants, so all models should not be suggested in identifying high-risk loan applicants. 
