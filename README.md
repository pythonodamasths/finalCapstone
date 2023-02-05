# finalCapstone
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Usage](#usage)

## General info
FinalCapstone is a project that performs principal component analysis (PCA) and application of two clustering techniques on the US Arrests dataset. The goal of the project is to understand the structure of the dataset and analyse the clusters they generate.

## Technologies
Windows
python
pandas
numpy
matplotlib
sklearn
seaborn
scipy

## Setup
To run this project, install it locally using Jupyter notebook

## Usage
The project contains the following steps:
Load the US Arrests dataset
Perform PCA analysis
Generate the PCA Report
Plot the PCA biplot
Calculate feature importance
Plot the cumulative variance explained by the components
Standardize the data
Perform K-means clustering
Plot the clusters
Perform Hierarchical Clustering
Plot the dendrogram
PCA Report
The PCA report includes:

#Standard deviation of each Principal Component
Proportion of Variance Explained
Cumulative Proportion of Variance Explained
PCA Biplot
The PCA biplot shows the relationship between the features and the principal components. Each feature is represented as an arrow pointing in the direction of maximum variance.

#Feature Importance
The feature importance table shows the contribution of each feature to the two principal components. The features are ranked in descending order of importance.

#Cumulative Variance Explained
The cumulative variance explained plot shows the cumulative proportion of variance explained by the number of components.

#K-means Clustering
The project performs K-means clustering on the standardized dataset to group similar data points into clusters. The number of clusters is set to 4.

#Hierarchical Clustering
The project performs Hierarchical Clustering on the standardized dataset to form a tree-based representation of the clusters. The dendrogram shows the relationships between the clusters.
