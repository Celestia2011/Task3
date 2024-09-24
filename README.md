Lab 3: CART Decision Tree with Pre-Pruning

Subject: Predictive Analysis
Dataset Information

For this lab, we use the Tennis Dataset again, which consists of various weather-related attributes such as outlook, temperature, humidity, wind, and the target variable 'play,' indicating whether tennis can be played.


The goal is to apply the CART decision tree (using entropy) and explore various pre-pruning techniques to develop models that predict whether tennis can be played based on the weather conditions.
Task Breakdown
Task A: CART Decision Tree with Pre-Pruning

    Data Preparation
        The dataset is split into training and testing sets to evaluate model performance.

    CART Decision Tree
        A decision tree model is developed using CART (with entropy) to evaluate the impact of various pre-pruning techniques.

    Pre-Pruning Methods
    We explore the following pre-pruning techniques:
        Maximum Depth: Limits the depth of the tree.
        Minimum Samples Split: The minimum number of samples required to split an internal node.
        Minimum Samples Leaf: The minimum number of samples that a leaf node must have.
        Maximum Features: Limits the number of features to consider when looking for the best split.

    Application of Pre-Pruning Techniques
    Each pre-pruning method is applied independently, and the model is trained and evaluated. The performance metrics (such as accuracy, precision, recall, F1-score) are recorded for each pruning technique.

    Visualization of Decision Trees
    A visual representation of the decision tree is generated for each pre-pruning scenario to observe how the tree structure changes.

    Comparative Analysis
    A comparative analysis is performed to evaluate the impact of each pre-pruning method on model performance, overfitting, and complexity.
