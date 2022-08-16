# Credit_Risk_Analysis

### Introduction
We are attempting to predict credit risk using six different machine learning algorithms. With the help of LendingClubs dataset, we have come to a conclusion on whether or not an algorithm was the most successful for our purposes.

### Results
![RandomOversampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/RandomOversampling.png)
##### This figure contains the code for our random oversampling analysis.
* Accuracy = 0.651
* Precision = 0.010
* Sensitivity = 0.007
<br />

![SMOTEOversampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTEOversampling.png)
##### This figure contains the code for our SMOTE oversampling analysis.
* Accuracy = 0.655
* Precision = 0.011
* Sensitivity = 0.005
<br />

![UnderSampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Undersampling.png)
##### This figure contains the code for our undersampling analysis.
* Accuracy = 0.600
* Precision = 0.008
* Sensitivity = 0.007
<br />

![SMOTEENNSampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTEENN.png)
##### This figure contains the code for our SMOTEENN analysis.
* Accuracy = 0.681
* Precision = 0.010
* Sensitivity = 0.008
<br />

![RandomForestSampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/RandomForest.png)
##### This figure contains the code for our Random Forest analysis.
* Accuracy = 0.683
* Precision = 0.88
* Sensitivity = 0.002
<br />

![EasyEnsemblerSampling](https://github.com/shaneabbley/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/EasyEnsembler.png)
##### This figure contains the code for our Easy Ensemble analysis.
* Accuracy = 0.932
* Precision = 0.086
* Sensitivity = 0.005
<br />

### Analysis

The above data clearly points to one fact, that is, none of the above models predict the credit card risk to a degree deemed satisfactory. This is because none of the above models correctly identify bad credit risk even a majority of the time. With some significant improvements to the recall, we could start to see some progress.


