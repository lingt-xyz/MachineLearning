# Linear Regression

Using the equation for a line, you could write down a relationship as follows:

$$
y=mx+b
$$

where:

* $$y$$is the temperature in Celsius—the value we're trying to predict.
* $$m$$is the slope of the line.
* $$x$$is the number of chirps per minute—the value of our input feature.
* $$b$$is the y-intercept.

By convention in machine learning, you'll write the equation for a model slightly differently:

$$
y' = b + w_1x_1
$$

where:

* $$y'$$is the predicted label \(a desired output\).
* $$b$$is the bias \(the y-intercept\), sometimes referred to as .
* $$w_1$$is the weight of feature 1. Weight is the same concept as the "slope" in the traditional equation of a line.
* $$x_1$$is a feature \(a known input\).

To **infer** \(predict\) the temperature $$y'$$for a new chirps-per-minute value $$x_1$$, just substitute the $$x_1$$ value into this model.

Although this model uses only one feature, a more sophisticated model might rely on multiple features, each having a separate weight \($$w_1, w_2$$, etc.\). For example, a model that relies on three features might look as follows:

$$
y' = b + w_1x_1 + w_2x_2 + w_3x_3
$$

