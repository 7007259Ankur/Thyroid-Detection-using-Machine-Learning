# Thyroid Detection using Machine Learning

## Introduction

With this Machine Learning Project, we will develop a hypothyroid disease detection model. For this project, we will be using two models: KNN (K-Nearest Neighbors) and Decision Tree.

### Hypo Thyroid Disease

Incidences of thyroid illness have increased recently. The thyroid gland plays a crucial role in controlling metabolism. Two of the most prevalent disorders caused by thyroid gland irregularities are hyperthyroidism and hypothyroidism. Each year, a substantial number of patients are diagnosed with thyroid conditions like hypothyroidism and hyperthyroidism. Levothyroxine (T4) and triiodothyronine (T3) are produced by the thyroid gland, and both hypothyroidism and hyperthyroidism can result from a lack of thyroid hormones.

Technological advancements in data processing and computation have made it possible to use machine learning and deep learning techniques for early-stage thyroid diagnosis. These techniques help in identifying various types of thyroid disease, such as hypothyroidism and hyperthyroidism, which can reduce medical costs and improve treatment efficiency.

### Choosing Models

Machine learning has provided multiple methods for classifying and detecting thyroid illness. For example, Garcia utilized machine learning methods like Random Forest (RF), Logistic Regression (LR), Gradient Boosting Machines (GBM), Support Vector Machine (SVM), and Deep Neural Networks (DNN) to predict thyroid hormone imbalances. According to research, the Decision Tree algorithm performed better than other methods like SVM, Naive Bayes (NB), and Multilinear Regression (MLR) in predicting thyroid disease with a 99.23% accuracy.

For this project, we will use **Decision Tree** and **KNN** models.

## Decision Tree

The **Decision Tree** is a supervised learning algorithm that splits the dataset into subsets based on feature values. The tree structure helps categorize input data based on its features. The Decision Tree follows these steps:
1. Create a tree using input features of the nodes.
2. Choose a feature to predict the result with the best information gain.
3. Repeat step 2 to create subtrees.

## KNN (K-Nearest Neighbors)

**KNN** is another supervised learning algorithm used for classification and regression. It is based on the principle that similar data points are located close to one another. KNN classifies new data points based on the proximity to the nearest neighbors. K is a parameter representing the number of nearest neighbors.

The Euclidean distance formula is used to compute the distance between two points `P` and `Q`:

\[
\text{Euclidean Distance} = \sqrt{(p_1 - q_1)^2 + (p_2 - q_2)^2 + \dots + (p_n - q_n)^2}
\]

## Project Prerequisites

To implement this project, you will need:

- **Python 3.6** installed.
- **Required Libraries**:
  - `Numpy (1.22.4)` – `pip install numpy`
  - `Pandas (1.5.0)` – `pip install pandas`
  - `Seaborn (0.9.0)` – `pip install seaborn`
  - `Sklearn (1.1.1)` – `pip install sklearn`

## Thyroid Detection Project & Dataset

You can download the required dataset and Jupyter notebook for this project from the following link: [Thyroid Detection Project](#).
