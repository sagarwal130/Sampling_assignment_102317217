# Sampling Assignment – Credit Card Fraud Detection

## Objective
The objective of this assignment is to study the importance of sampling techniques in handling highly imbalanced datasets and to analyze how different sampling strategies affect the performance of various machine learning models.

## Dataset
The Credit Card Fraud Detection dataset contains a large class imbalance, where normal transactions significantly outnumber fraudulent ones. This imbalance can lead to biased model predictions if not handled properly.

### Data Preprocessing
- The dataset was split into training and testing sets.
- Class imbalance was handled by balancing the training data using oversampling.
- Sampling techniques were applied only to the training data to prevent data leakage.

### Sampling Techniques Used
1. Simple Random Sampling
2. Systematic Sampling
3. Bootstrap Sampling
4. Cross-Validation Sampling
5. Stratified Random Sampling

### Machine Learning Models Used
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)

## Results
The performance of each model was evaluated using accuracy. Different sampling techniques produced different accuracy levels for each model, highlighting the impact of sampling on model performance.

## Analysis
- Logistic Regression performed best with Stratified Random Sampling.
- Decision Tree and Random Forest showed strong performance with Bootstrap Sampling.
- SVM benefited from Systematic and Stratified Sampling.
- KNN performed better with Simple Random Sampling.
- Random Forest performed best using Bootstrap Sampling. This result is expected because Random Forest internally uses bootstrapping to build multiple decision trees, making this sampling technique naturally compatible with the model.

## Conclusion
There is no single sampling technique that performs best for all machine learning models. The choice of sampling method should depend on the model and the nature of the dataset. Proper sampling significantly improves performance in imbalanced classification problems.

## Files in Repository
- Sampling_Assignment_Beginner.ipynb
- sampling_results_new_methods.csv
- README.md
