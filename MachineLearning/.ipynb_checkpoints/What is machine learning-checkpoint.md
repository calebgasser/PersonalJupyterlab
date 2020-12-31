# What is machine learning?

"Machine learning is the semi-automated extraction of knowledge from data"


* Knowledge from data: Starts with a question ahtat might be answerable using data
* Automated Extraction: A computer provides the insight
* Semi-automated: Requires many smart decisions by a human


# Two categories of machine learning

## Supervised learning (Predictive Modeling)

Making predicitons using data (a specific outcome)

* Example: Is a given email "spam" or "ham"?
* There is an outcome we are trying to predict 

![title](images/01_spam_filter.png)

## Unsupervised learning

Extracting structure from data or how to best represent it

* Example: Segment grocery store shoppers into clusters that exhibit similar behaviors
* There is no "right answer"

![title](images/01_clustering.png)

# How does machine learning "work"?

High-level steps of supervised learning:

1. First, train a machine learning model using labeled data
    * "Labeled data" has been labeled with the outcome
    * "Machine learning model" learns the relationship between the attributes of the data and its outcome
2. Then, make **predicitons** on **new data** for which the label is unknown.

![title](images/01_supervised_learning.png)

The primary goal of supervised learning is to build a model that "generalizes": It accurately predicts the **future** rather than the **past!**

# Questions about machine learning

* How do I choose **which attributes** of my data to include in the model?
* How do I choose **which model** to use?
* How do I **optimize** this model for best preformance?
* How do I ensure that I'm building a model that will **generalize** to unseen data?
* Can I **estimate** how well my model is likely to preform on unseen data?

# Resources

* Book: __[An Introduction to Statisctial Learning](http://www-bcf.usc.edu/~gareth/ISL/)__
* Video: __[Learning Paradigms](http://work.caltech.edu/library/014.html)__