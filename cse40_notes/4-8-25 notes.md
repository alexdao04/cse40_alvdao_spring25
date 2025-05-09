# CSE 40 Notes, April 8, 2025
Name: Alexander Dao

Machines don't learn. They find a mathematical formula, which applied to a collection of inputs ("training data") produces our desired outputs.
    - ML is a universally recognized term that refers to the science/engineering of building machines that can do various useful things without being explicitly programmed to do so.

ML Algorithms:
    Supervised Learning
        - Uses labeled examples of classes (types of things) to construct a classifier (model) that can make predictions about future objects.
    Unsupervised Learning
        - Organiz[es/Analyzes unlabeled observations to identify new categories/clusters
    Reinforcement Learning
        - Uses delayed feedback about actions performed in some environments to learn the value of actions taken in specific contexts.]

Different kinds of supervised ML:
Classification: Output one of a set of discrete labels
Regression: output a real number
Clustering: outputs groups of similar data points

Inputs #1:
Feature Vectors
A vector (represented as array) of features describing each example.

Notation:
1) x is an item/feature vector -> vector; x_i is the ith feature.
2) x_i is an item/feature vector -> x_ij is the jth feature of the ith input vector.

Input Data #2: Labels
A label is the correct classification (desired output) associated with a particular input feature vector

ML Output: Hypothesis
A tentative explanation for a observation, phenomenon, or scientific problem we can test and investigate.

Mathematical function we learn from data is our hypothesis (simplifying things a bit)

Optimization formula (supervised ML)
