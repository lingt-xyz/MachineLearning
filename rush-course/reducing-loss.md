# Reducing Loss

### [Convergence](https://developers.google.com/machine-learning/glossary/#convergence)

Informally, often refers to a state reached during training in which training loss and validation loss change very little or not at all with each iteration after a certain number of iterations. In other words, a model reaches convergence when additional training on the current data will not improve the model. In deep learning, loss values sometimes stay constant or nearly so for many iterations before finally descending, temporarily producing a false sense of convergence.

### [Gradient Descent](https://developers.google.com/machine-learning/crash-course/reducing-loss/gradient-descent)

A technique to minimize loss by computing the gradients of loss with respect to the model's parameters, conditioned on training data. Informally, gradient descent iteratively adjusts parameters, gradually finding the best combination of weights and bias to minimize loss.

### [Learning Rate](https://developers.google.com/machine-learning/crash-course/reducing-loss/learning-rate)

A scalar used to train a model via gradient descent. During each iteration, the gradient descent algorithm multiplies the learning rate by the gradient. The resulting product is called the gradient step.

### [Stochastic Gradient Descent \(SGD\)](https://developers.google.com/machine-learning/crash-course/reducing-loss/stochastic-gradient-descent)

A gradient descent algorithm in which the batch size is one. In other words, SGD relies on a single example chosen uniformly at random from a dataset to calculate an estimate of the gradient at each step.  


