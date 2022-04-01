# Loan Risk Analysis

## Overview

<p>The purpose of this analysis is to see which machine learning classifier performs best at identifying high and low risk loan applications.</p>

## Results

<p>Below are the results for each of the 6 classifers used in this analysis. For our analysis we are focused on the Balanced Accuracy, Precision, and Recall scores.</p>

Balanced Accuracy Score<br/>
<img src="../main/images/BAScores.png" width='290'>

Naive Random Oversampling<br/>
<img src="../main/images/CR_random_oversample.png" width='478'>

SMOTE Oversampling<br/>
<img src="../main/images/CR_smote_oversample.png" width='478'>

Undersampling<br/>
<img src="../main/images/CR_undersample.png" width='478'>

Combination Oversampling/Undersampling<br/>
<img src="../main/images/CR_combo.png" width='478'>

Balanced Random Forest<br/>
<img src="../main/images/CR_BRForest.png" width='478'>

Easy Ensemble AdaBoost<br/>
<img src="../main/images/CR_EEAdaBoost.png" width='478'>


## Summary

<p>In conclusion, we can see that oversampling and undersampling produced similar, but average predicition results. While the Balance Random Forest and Easy Ensemble classifiers predicted the loan risk much more often. Given the precision and recall scores of the Easy Ensemble, which are both at or near 1.0, as well as higher balanced accuracy scores, i would recommend using that classifier for doing further loan risk analysis.</p>

summary
recommendation on which model to use with justification
