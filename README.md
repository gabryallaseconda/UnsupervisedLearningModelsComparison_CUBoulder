# Unsupervised Models Comparison for Classification on Wine Quality dataset

Project for Deep Learning at CU Boulder

Data from UCI repository ([Link](https://archive.ics.uci.edu/dataset/186/wine+quality))

Some techniques of Unsupervised Learning can be adapted to be used also for classification.

Code is organized as follows:
- Exploratory.ipynb contains exploratory analysis and data preprocessing;
- M1-PCARegression.ipynb uses PCA to reduce the dimensionality of the training data and a linear model to perform the classification;
- M2-MatrixFactorization.ipynb uses SVD to factorize training data and uses permutation to match the labels.
- M3-HierarchicalClustering.ipynb uses Hierarchical Clustering to label the data, matching through permutation.
- submission.ipynb is a merge of the previous notebookst for CU Boulder submission.
