# Iris Dataset Analysis
## Introduction

The Iris dataset is a well-known dataset in the field of machine learning, containing 150 samples of iris flowers with features such as sepal length, sepal width, petal length, and petal width. 
The goal of this project is to:

1. **Classify** the iris species using the K-Nearest Neighbors (KNN) algorithm.
2. **Cluster** the data using the K-Means algorithm to explore the natural groupings of the iris species.

## Requirements

The following Python libraries are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

# Insights
Through this analysis, several key insights were gained:

## Species Differentiation:

- The species Iris-setosa is easily separable from the other two species (Iris-versicolor and Iris-virginica) based on the features in the dataset, especially petal length and width.
- Iris-versicolor and Iris-virginica show some overlap, making them more challenging to classify.

## Feature Importance:

- Petal dimensions (length and width) are more significant in distinguishing between different iris species compared to sepal dimensions.
This is evident in the visualization plots where clear clusters form when petal features are plotted against each other.

## Model Performance:

- The K-Nearest Neighbors (KNN) algorithm achieved high accuracy in classifying the iris species, demonstrating the effectiveness of KNN on well-separated classes.
- K-Means clustering aligned well with the actual species labels, particularly for Iris-setosa, but showed some misalignment between Iris-versicolor and Iris-virginica due to their overlap.

## Clustering Analysis:

K-Means clustering revealed that the natural groupings within the data closely resemble the actual species divisions, suggesting that the features in the dataset are strong indicators of species.

