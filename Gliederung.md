### Gliederung BA Simon Wastl

# Neural Nets on Credit Card Fraud Detection

## Gliederung
1. Abstract
2. Related Work
3. Method
    1. Problem Definition
    2. Model
    3. Optimizer
4. Experimental Results
    1. Dataset
    2. Preprocessing
    3. Evaluation Metrics
    4. Methods and Performance Evaluation
    5. Discussion
5. Conclusion and Perspective
6. References

## Abstract
The first impression of the work. Tries to explain every part of the paper in around two sentences each and create interest in the paper. Will be created last.

## Motivation
Motivation serves as the real introduction. You state the problem and its importance. Afterwards, explain the solution and your method to create this solution. It's important to address the target group, use of the knowledge and reason for research. After reading the motivation, the reader should have clear vision of what to expect from this paper.

## Methodology
The method in this case is machine learning. Via feed-forward Neural Net, you train an algorithm to build a model for predicting unseen data. To do this, we have to do different tasks:

1. Data Preprocessing (Imbalanced Data, Duplicates)
2. Data Normalization (Standard Normal Distribution Scaling)
3. Train/Test split (Split data into 'Seen' and 'Unseen' Data. 80/20 Cross Validation probably.)
4. Training (Load Data into Model and train batches in epochs, compare regression)
5. Testing (Load Model into Test Split to measure performance on unseen Data)
6. Hyperparameter-Tuning (To increase performance on unseen Data, batch-size, epochs, layers 
    and learning rate may be altered)

