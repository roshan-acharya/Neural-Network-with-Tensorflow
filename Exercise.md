# Machine Learning Notes

Welcome to repository! I will be using this document to organize exercises, questions and notes as I learn.


## Table of Contents

- [Exercise PCA ](#questions )


---



---

## Questions


```markdown
### Question 1 :  What are the main motivations for reducing a dataset’s dimensionality? What are the main drawbacks?
- The main motivation for reducing a dataset's dimensionality are:
1. Reduces Training complexity
2. Higher dimesional data are difficult to          visualize  

## Drawbacks
1. Loss of information
2. Difficult to intrepret

### Question 2 : What is the curse of dimensionality?
- 1. Complexity in training
- 2. Higher dimensional data are difficult to visualize  

### Question 3 : Once a dataset’s dimensionality has been reduced, is it possible to reverse the operation? If so, how? If not, why?
- Yes, It is possible to reverse the operation using inverse_transform() but we cannot perfectly reconstruct it for PCA only

### Question 4 : Can PCA be used to reduce the dimensionality of a highly nonlinear dataset?

- Yes, Using Kernel PCA

### Question 5 : Suppose you perform PCA on a 1,000-dimensional dataset, setting the explained variance ratio to 95%. How many dimensions will the resulting dataset have?


### Question 6 :  In what cases would you use vanilla PCA, Incremental PCA, Randomized PCA, or Kernel PCA?

- 1. Vanilla PCA : For small dataset.
- 2. Incremental PCA : For batch training by splitting training data
- 3. Randomized PCA : For fast processing. 
- 4. Kernel PCA : Non-linear dataset

```

