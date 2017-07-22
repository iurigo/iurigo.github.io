---
layout: post
title: Regression Modeling
---

### Introduction to Regression Modeling

# Model-based inference

- We can use models to conduct inference.
- Given a model, we can better understand relationships between an independent variable and the dependent variable or between multiple independent variables.

# Prediction

- We can use a model to make predictions, or to estimate an dependent variable's value given at least one independent variable's value.
- Predictions can be valuable even if they are not exactly right.
- Good predictions are extremely valuable for a wide variety of purposes.

create an x and a y that is
50 plus 2 times x with some random noise around that
x = np.linspace(-5, 50, 100)
y = 50 + 2 * x  + np.random.normal(0, 20, size=len(x))

df = pd.DataFrame({'X': x, 'Y': y})
df.head()

![](/images/Screen Shot 2017-07-21)
