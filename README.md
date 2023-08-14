# dec-tree

## Techniques Used
- Recursive Splitting
- Stopping Conditions
- Bootstrap Aggregating (Bagging)
- Feature Randomization
- AdaBoost 
- Adaptive Weighting
- Ensemble Weighting
- Model Comparison
- Random Forrest
- Decision Tree
- Variance Reduction
- Overfitting Prevention
- Loss Functions(Gini Impurity, Entropy, and Misclassification Error)

  ## Functionality
  - Decision Tree Implementation
    - The DecisionTree class is implements a fit method that grows a decision tree using the provided training data. It iteratively selects features and thresholds to split nodes based on criteria like entropy, Gini impurity, or misclassification error.
    - The predict method traverses the decision tree to make predictions for the provided samples.
  
  - Random Forest Implementation
    - The RandomForest class wraps the DecisionTree class and trains an ensemble of decision trees, where each tree is trained on a random subset of features and samples.
    - The predictions from each tree are combined to make the final prediction.

- AdaBoost Implementation
  - The AdaBoost class here adapts decision trees to improve classification accuracy.
by training multiple weak learners (decision trees) sequentially, giving more emphasis to misclassified samples.
  - Learners are assigned weights based on their performance, and their predictions are aggregated to make final predictions.

- Model Training and Evaluation
  - The code trains various models like Decision Trees, Random Forests, and AdaBoost on different datasets.
  - The accuracy of each model is evaluated on both the training and test datasets.

-Sample Usage and Experimentation
  - The code includes an example of how to create a decision tree, train a random forest, and use AdaBoost from scratch.
  - It also demonstrates how to create a synthetic dataset and evaluates the accuracy of a decision tree on this dataset.
