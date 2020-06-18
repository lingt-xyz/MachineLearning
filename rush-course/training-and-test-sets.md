# Training and Test Sets

### [Splitting Data](https://developers.google.com/machine-learning/crash-course/training-and-test-sets/splitting-data)

Divide your data set into two subsets:

* training set—a subset to train a model.
* test set—a subset to test the trained model.

Make sure that your test set meets the following two conditions:

* Is large enough to yield statistically meaningful results.
* Is representative of the data set as a whole. In other words, don't pick a test set with different characteristics than the training set.

### Classic gotcha: do not train on test data

* Getting surprisingly low loss?
* Before celebrating, check if you're accidentally training on test data

