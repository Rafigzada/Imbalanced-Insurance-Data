# Imbalanced-Insurance-Data

## Overview
This repository addresses the challenge of imbalanced datasets using a resampling symphony. The dataset initially displayed a significant imbalance between class 0 and class 1 instances, prompting the application of innovative solutions to ensure effective model training. This journey encompasses data preprocessing steps and the strategic use of resampling techniques to rectify the imbalance.

## Data Preprocessing
Outlier Removal in 'Annual_Premium':

Surgically removed outliers in 'Annual_Premium' using statistical measures for dataset robustness.
Setting the Stage: 'Response' as the Target:

Designated 'Response' as the target variable for model focus.
Streamlining Features: Farewell to 'Driving_License':

Removed 'Driving_License' feature for efficiency.
Resampling Symphony
Initial Imbalance Metrics:
Mean ROC-AUC: 0.8858
Mean Recall: 0.0000
Mean Precision: 0.0000
Mean F1 Score: 0.0000
Mean Accuracy: 0.8362
1. StratifiedKFold Cross-Validation:
Employed StratifiedKFold cross-validation to fortify against overfitting.
2. Random Forests Take the Stage:
Introduced RandomForestClassifier known for handling imbalanced datasets.
3. RandomOverSampler to the Rescue:
Applied RandomOverSampler with a tailored sampling strategy for the minority class.
4. SMOTE: Crafting Synthetic Harmony:
Continued the resampling journey with SMOTE to introduce synthetic instances.
Balanced Metrics:

## After RandomOverSampler:

Mean ROC-AUC: 0.8849
Mean Recall: 0.9360
Mean Precision: 0.3995
Mean F1 Score: 0.5599
Mean Accuracy: 0.7589

## After SMOTE:

Mean ROC-AUC: 0.8741
Mean Recall: 0.9013
Mean Precision: 0.4196
Mean F1 Score: 0.5726
Mean Accuracy: 0.7796
## Conclusion
In the finale of our resampling symphony, the once-imbalanced dataset now stands as a beacon of equilibrium. The model, once shackled by skewed proportions, now glides with finesse, boasting improved metrics and a newfound capacity to navigate the complexities of real-world scenarios. This tale serves as a testament to the transformative power of resampling, with RandomOverSampler and SMOTE emerging as unsung heroes reshaping our data landscape.
