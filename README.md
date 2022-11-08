# KNN_to-find-out-the-car-for-the-user
Steps to implement the K-NN algorithm:

Data Pre-processing step
Fitting the K-NN algorithm to the Training set
Predicting the test result
Test accuracy of the result(Creation of Confusion matrix)
Visualizing the test set result.
Fitting K-NN classifier to the Training data:
Now we will fit the K-NN classifier to the training data. To do this we will import the KNeighborsClassifier class of Sklearn Neighbors library. After importing the class, we will create the Classifier object of the class. The Parameter of this class will be
n_neighbors: To define the required neighbors of the algorithm. Usually, it takes 5.
metric='minkowski': This is the default parameter and it decides the distance between the points.
p=2: It is equivalent to the standard Euclidean metric.
