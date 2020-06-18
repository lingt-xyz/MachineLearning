# 6 Step Machine Learning Framework

## 1. Problem Definition

## 2. Data

## 3. Evaluation

Different types of metrics

| Classification | Regression | Recommendation |
| :--- | :--- | :--- |
| Accuracy | Mean absolute error \(MAE\) | Precision at $$K$$ |
| Precision | Mean squared error \(MSE\) |  |
| Recall | Root mean squared error \(RMSE\) |  |

## 4. Features

Different features of data

* Numerical features
* Categorical features

### Feature coverage

How many samples have different features? Ideally, every sample has the same features.

* One feature should have more than 10% coverage to be considered useful.

## 5. Modelling

### 3 parts to modelling

1. Choosing and training a model: training data
2. Tuning a model: validation data
3. Model comparison: test data

### 3 data sets

1. Training data set 
2. Validation/development data set
3. Test data set

Generalization: The ability for a machine learning to model to perform well on data it hasn't seen before. 

Overfitting and underfitting: Goldilocks zone

{% hint style="danger" %}
Overfitting: data leakage. Test data leaks into training data

Underfitting: data mismatch. Test data is different from the training data
{% endhint %}

{% hint style="success" %}
Fixes:

Underfitting:

1. Try a more advanced model
2. Increase model hyperparameters
3. Reduce the amount of features
4. Train longer

Overfitting:

1. Collect more data
2. Try a less advanced model
{% endhint %}

## 6. Experiments

