# Linear Regression

#### Simple Linear Regression

Simple linear regression models the relationship between two variables using a linear equation. It is used to understand how a change in one input variable is related to a change in the predicted output.

The equation used is:

> **ŷ = b + wx**

- **ŷ** is the predicted output (predicted label).
- **b** is the y-intercept, also called the bias of the model.
- **w** is the weight, also called the slope in simple linear regression.
- **x** is the input feature.

In simple linear regression, there is one input feature. In linear regression with multiple features, more than one input can be used.

---

#### Feature / Input

A **feature** is an input given to the model. The output of the model depends on the information provided by the features.

A model can have one feature or multiple features. For example, if we want to predict exam marks using study hours:

- **Feature (input):** Hours studied
- **Target (output):** Exam marks

The model uses the input feature to make a prediction about the target.

---

#### Target Variable

The **target variable** is the value that we want the model to predict. It is also called the label or output.

For example:

> Hours studied → Model → Predicted exam marks

Here, hours studied is the feature and exam marks is the target variable.

The prediction error can be represented as:

> **ε = y - ŷ**

where:

- **y** is the actual target value.
- **ŷ** is the predicted value.
- **ε** is the difference between the actual and predicted value.

For example, if the actual value is 80 and the predicted value is 75:

> Error = 80 - 75 = 5

---

#### Slope

The **slope** is represented by **m** in the standard equation:

> **y = mx + b**

In a machine learning model, the slope is commonly represented by the **weight (w)**.

genui{"learning_viz":{"type_id":"SLOPE_INTERCEPT","initial_values":{"slope":2,"intercept":3}}}

If the graph is 2D and there is one feature, the model produces a straight line. The slope tells us how much the predicted output changes when the input feature changes by one unit.

For example, if the slope is 2, increasing x by 1 increases the predicted y by 2.

---

#### Intercept

The **intercept** is represented by **b** in the equation:

> **y = mx + b**

The intercept is the point where the straight line crosses the **Y-axis**. It represents the predicted value of y when x is 0.

In machine learning, the intercept is also commonly called the **bias**.

---

#### How the Model Learns

During training, the model learns the values of the **weight (slope)** and **bias (intercept)**.

A loss function is used to measure how far the predictions are from the actual values. An optimization method such as **gradient descent** can then update the weight and bias so that the loss becomes smaller.

In simple terms:

> **Model makes predictions → calculate loss → update weight and bias → repeat**

The goal is to find parameters that produce predictions with low error on the training data.

---

#### Overfitting

**Overfitting** happens when a model learns the training data too closely, including noise or patterns that do not generalize to new data.

It can happen because of reasons such as:

- Too many variables/features
- Not enough training data
- A model that is too complex
- High variance

An overfitted model can perform very well on training data but poorly on unseen data.

---

#### Underfitting

**Underfitting** happens when the model is too simple to capture the important patterns in the data.

For example, if the real data contains a complex relationship but we use a model that is too simple, the model may fail to represent that relationship properly.

An underfitted model usually performs poorly on both the training data and unseen data.

---

#### Prediction Error

**Prediction error** is the difference between the actual value and the predicted value.

> **Prediction error = Actual value - Predicted value**

A larger error means that a particular prediction is farther from the actual value.

For many predictions, metrics such as **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)** can be used to summarize the errors.

---

# Case Studies

#### Using Linear Regression Analysis to Predict Energy Consumption

> Reference: https://www.researchgate.net/publication/381955955_Using_Linear_Regression_Analysis_to_Predict_Energy_Consumption

Researchers from Vietnam used linear regression to predict energy consumption in practical applications using data from IoT systems.

The study used linear regression in three case studies to predict electricity and gas consumption. Features were used as inputs to the prediction model, while actual energy consumption values were used as target values.

The researchers compared the predicted values with the actual consumption values and evaluated the model using error and correlation measures.

---

# What I Learned

I learned that simple linear regression is used to model the relationship between one input feature and a target using a straight-line equation.

The main concepts I understood were the feature, target variable, slope, intercept, prediction error, overfitting, and underfitting.

I also learned that the model learns its weight (slope) and bias (intercept) during training. Gradient descent can be used to update these parameters by reducing the loss.

One thing I initially found confusing was the difference between prediction error and metrics such as MSE and MAE. A prediction error describes the difference for an individual prediction, while MSE and MAE summarize errors across multiple predictions.

---

# Beginner-Friendly Summary

In simple terms, linear regression tries to draw a line that represents the relationship between an input and an output.

For example:

> **Hours studied → Linear Regression Model → Predicted Exam Marks**

The model learns the **slope (weight)** and **intercept (bias)** of the line. It uses these values to make predictions and tries to reduce the difference between its predictions and the actual values.

The main idea is:

> **Input → Prediction → Calculate Error → Improve the Model**

---

# Review Status

Ready for review.
