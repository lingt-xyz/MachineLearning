# Training and Loss

**Training** a model simply means learning \(determining\) good values for all the weights and the bias from labeled examples. In supervised learning, a machine learning algorithm builds a model by examining many examples and attempting to find a model that minimizes loss; this process is called **empirical risk minimization**.

Loss is the penalty for a bad prediction. That is, **loss** is a number indicating how bad the model's prediction was on a single example. If the model's prediction is perfect, the loss is zero; otherwise, the loss is greater. The goal of training a model is to find a set of weights and biases that have low loss, on average, across all examples.

Mean square error \(MSE\) is the average squared loss per example over the whole dataset. To calculate MSE, sum up all the squared losses for individual examples and then divide by the number of examples:

$$
MSE = \frac{1}{N} \sum_{(x,y)\in D} \big(y - prediction(x)\big)^2
$$

where:

* $$(x, y)$$is an example in which
  * $$x$$is the set of features \(for example, chirps/minute, age, gender\) that the model uses to make predictions.
  * $$y$$is the example's label \(for example, temperature\).
* $$prediction(x)$$is a function of the weights and bias in combination with the set of features .
* $$D$$is a data set containing many labeled examples, which are $$(x, y)$$pairs.
* $$N$$is the number of examples in $$D$$.

Although MSE is commonly-used in machine learning, it is neither the only practical loss function nor the best loss function for all circumstances

