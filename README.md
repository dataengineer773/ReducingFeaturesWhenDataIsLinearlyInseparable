We suspect you have linearly inseparable data and want to reduce the dimensions, Use an extension of principal component analysis that uses kernels to allow for non-linear
dimensionality reduction, PCA is able to reduce the dimensionality of our feature matrix (e.g., the number of features). Standard
PCA uses linear projection to reduce the features. If the data is linearly separable (i.e., you can draw a
straight line or hyperplane between different classes) then PCA works well. However, if your data is not
linearly separable (e.g., you can only separate classes using a curved decision boundary), the linear
transformation will not work as well. In our solution we used scikit-learn’s make_circles to generate a
simulated dataset with a target vector of two classes and two features. make_circles makes linearly
inseparable data; specifically, one class is surrounded on all sides by the other class, 
