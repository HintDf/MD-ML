# Principal Component Analysis
You can get more information from
[WikiWand](https://www.wikiwand.com/en/Principal_component_analysis).

## Define and Roles
> PCA is a statistical procedure that use an orthogonal transformation to convert a set of
observations of possibly correlated variables into a set of values of linearly uncorrelated
variables called **principle component**

> In order to work effectively with high-dimensional datasets, it is important to have a set of 
techniques that can reduce this dimensionality down to manageable levels. 
The advantages of this dimensionality reduction include the ability to plot multivariate 
data in two dimensions, capture the majority of a dataset's informational content 
within a minimal number of features, and, in some contexts, identify collinear model components.

> PCA is probably the most widely-used dimensionality reduction technique.



## Details

1. Identifying the center point of dataset
2. Calculating the covariance matrix of data
3. Calculating the eigenvectors of the covariance matrix
4. Orthonormalizing the eigenvectors
5. Calculating the proportion of variance represented by each eigenvectors

## Advantages

## Disadvantages
A particular disadvantage of PCA is that the principal components are usually linear combinations of all input variables. Sparse PCA overcomes this disadvantage by finding linear combinations that contain just a few input variables.