# MiningWearableData_ait
### Data Source
- Data set from UCI archive: http://archive.ics.uci.edu/ml/datasets/Wearable+Computing%3A+Classification+of+Body+Postures+and+Movements+%28PUC-Rio%29 

### Objective: Evaluate the performance of different classifiers on the wearable dataset
- Evaluate against labelled class using confusion matrix and accuracy measures - we care about how many % of data is correctly classified
- Test supervised learning with cross-validation (test/training data split) on data points to predict their motion classes, then calculate precision/recall/f1 score and accuracy against their true classes
  - Learning model includes KNN, Decision Tree, Neural Networks
- Run unsupervised clustering and see whether the clusters are interpretable; compare the interpreted cluster results with their true classes and see whether it outperforms supervised learning
  - Learning model includes K-Means.
  
### Presentation:
- Access at link: https://docs.google.com/presentation/d/1BprGk6AnJ3z5_Cj4s5UrqaL0lSnqkFB8GoAUEOiBdfg/edit?usp=sharing
