# Multiclassification-in-Logistic-Regression

The project includes the code I wrote to solve the multiclassification problems in logistic regression where I was asked to build a logistic regression to recognize handwritten digits(from 0 to 9). 

The basic idea is almost the same as that of logistic regression except for the fact that every function has to be vectorized such as vectorize the cost function, vectorize the gradient, vectorize the regularized logistic regression. The classification idea here is that I use one-vs-all which I classify one number as 1 and take the other number as 0. The accuracy is 94.9% which is relatively high. However, the multiclassification in logistic regression is computationally expensive--it takes me a lot of time to train it. 
