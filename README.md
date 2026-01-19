# Sampling Assignment – Credit Card Fraud Detection

## Objective
To study the impact of different sampling techniques on machine learning models when handling an imbalanced dataset.

## Dataset
Credit Card Fraud Dataset containing highly imbalanced classes.

## Sampling Techniques Used
1. Random Oversampling
2. Random Undersampling
3. SMOTE
4. NearMiss
5. SMOTE + Tomek Links

## Machine Learning Models Used
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine
5. K-Nearest Neighbors

## Analysis
- Logistic Regression achieved the highest accuracy using **SMOTE (93.53%)**, indicating that synthetic oversampling improves linear decision boundaries.
- Decision Tree performed best with **SMOTE (98.71%)**, as tree-based models handle synthetic samples effectively.
- Random Forest achieved the highest accuracy with **Random Oversampling (99.14%)**, benefiting from increased minority class representation.
- KNN showed the best performance with **Random Oversampling (97.84%)**, as additional minority samples improved neighborhood-based classification.

## Results
Different sampling techniques perform differently depending on the model.  
There is no single best sampling method for all models.

## Conclusion
Sampling plays a critical role in improving fraud detection performance on imbalanced datasets.
