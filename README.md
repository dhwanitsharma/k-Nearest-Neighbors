# k Nearest Neighbors

In this project, I have implemented a K-Nearest Neighbor classifier from scratch and use it on threedatasets: iris dataset, banknotes dataset, and MNIST dataset. 

### Iris Dataset
The description of data is given below:
First column: sepal length in cm
Second column: sepal width in cm
Third column: petal length in cm
Fourth column: petal width in cm
Fourth column: Class label

#### Implementations
1.Compare all four features distribution in each iris class using boxplots.
2.Start with k = 1, plot the decision boundary using the first two features (Sepal length and width)
3.Perform the prediction using k = 2, 4, 6, 10 and plot the decision boundaries.
4.For all cases, report accuracy and confusion matrix


### Bank notes Dataset
The description of data is given below:
First column: Variance of Wavelet Transformed image
Second column: Skewness of Wavelet Transformed image
Third column: Kurtosis of Wavelet Transformed image
Fourth column: Entropy of image
Fourth column: Class label

#### Implementations
1.Perform a 2-nearest neighbor on bank note dataset using 80% of the data as training data and the rest as test. Report the accuracy and confusion matrix.
2.Use two new distance measures: Manhattan distance and L3 (Minkowski formula for p = 3), and redo the previous step.
3.For all cases, report accuracy and confusion matrix.


### MNIST Dataset
In MNIST, each image contains a single grayscale digit drawn by hand. And each image is a 784 dimensional vector (28 pixels for both height and width) of floating-point numbers where each value represents a pixel’s brightness.

#### Implementations
1.Perform the 2-nearest neighbors on MNIST dataset using 500, 1000, 2500, 5000,and 10000 training examples. How does the classification error change with number of training example? plot it.
2.Report confusion matrix of the best model?





### Tech Stack
Python

### Libraries Used
pandas

seaborn

numpy

matplotlib

sklearn
