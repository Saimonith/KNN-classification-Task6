# KNN-classification-Task6
KNN-classification-Task6
## objective
Implement k-nearest neighbour algorithm for classification problems using python , scikit-learn , pandas , and matplotlib.
## Tools& Libraries Used
python
pandas
Numpy
Matplotlib
Scikit-learn
## Dataset
Dataset used:**Iris dataset**
You can download from:[Iris Dataset Link](https://archive.ics.uci.edu/ml/dataset/iris)
## steps followed 
**DataLoading&Exploration**
Loaded dataset using pandas
checked shape, column names, and first few rows.
**Data preprocessing**
selected features and target variable.
Normalized feature using'standardscaler'
**model Training**
Used'KNeighborsclassifier'from scikit-learn.
Tried multiple values of 'k' to find best accuracy.
**evaluation**
Used**accuracy score** and **confusion matrix**.
plotted decision boundaries for visualization.
## Results
Best Accracy:**96%** with k=5
confusion matrix:
![confusion matrix](confusion_matrix.png)
## Decision Boundary Visualization
![Decision boundary](decision-boundary.png)
