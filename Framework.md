# Tha Framework to Approach Machine Learning Problems

You can refer to a more complete blog post about this framework impplementation [here](https://www.mrdbourke.com/a-6-step-field-guide-for-building-machine-learning-projects/).

## Main types of ML

1. Supervised learning (data with labels)

  * Classification (binary or multiclass)
  * Regression (predicting a number)

2. Unsupervised learning (data with no labels)

3. Transfer learning

  * Existing models applied to different problems

4. Reinforcement learning

  * Teaching machines via 'rewards' and 'punishments'

## 1. Problem Definition

What problem am I trying to solve?

## 2. Data

What kind of data do I have?

### Types of Data

1. Structured
This is what you would typically expect from csv files.

2. Unstructured Data
Coming in various formats like audio and images.

Whithin those mentioned, we may have static (persistent) data or streaming (changing overtime) data.

## 3. Evaluation

What is considered success in the case of a certain experiment?

### Different Metrics (may vary)

* Classification: Accuracy, Precision, Recall
* Regression: Mean Absolute and Squared Error

## 4. Features

What do I already know about the data?

We divide our data into the features (variables to help us know the target) and the target (the variable we expect to predict)

Types of features: categorical or numerical

## 5. Modelling

What ML algorithm should I use for the problem we face?

### Sets

The data we have must be splitted:

1. We must train our model with training data (around 70%)
2. The validation data will serve for finetuning our model (around 15%) // this set is sometimes overlooked
3. The testing set of data will serve us to grade our model (around 15%)

### Models

Some models to work on structured data are decision trees

Some models to work on unstructured data are neural networks (deep learning - not covered in this github but coming up)

### Tuning

Models have hyperparameters which allow us to 'edit their settings' to experiment and aim for better metric results.

### Comparison

Some terms to remember:

* Underfitting: the model is not learning
* Overfitting: the model is memorizing
* The key is to be inbetween them.

## 6. Experimentation

How can I improve or what to try next?