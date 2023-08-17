# Advanced_SVM_Classification - End to End Implementation
There are 24 features, or columns, in X. This is a problem because it would require a 24-dimensional graph, one dimension per feature used to make predictions, to plot the data in its raw form. If we wanted to, we could just pick two features at random to use as x and y-axes on our graph, but instead, we will use PCA (Principal Component Analysis) to combine the 24 features into 2 orthogonal meta-features that we can use as axes for a graph.

However, before we shrink the graph, let's first determine how accurate the shrunken graph will be. If it's relatively accurate, than it makes sense to draw the 2-Dimensional graph. If not, the shrunken graph will not be very useful. We can determine the accuracy of the graph by drawing something called a scree plot.

scree plot: - In multivariate statistics, a scree plot is a line plot of the eigenvalues of factors or principal components in an analysis. The scree plot is used to determine the number of factors to retain in an exploratory factor analysis (FA) or principal components to keep in a principal component analysis (PCA).
![image](https://github.com/Abhiashu10/SVM-and-PCA/assets/101308486/d731107f-ebd6-444b-bda3-6814e46132dc)

![image](https://github.com/Abhiashu10/SVM-and-PCA/assets/101308486/977f9e7e-cd7a-45d4-9a5d-df5c7b5be43b)
