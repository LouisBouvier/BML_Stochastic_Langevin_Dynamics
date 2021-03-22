# Bayesian Machine Learning project: Stochastic Langevin Dynamics

This repository contains the code for the implementations of the principles of Bayesian Learning via Stochastic Gradient Langevin Dynamics (SGLD), Max Welling and Yee Whye Teh (2011): http://www.icml-2011.org/papers/398_icmlpaper.pdf. 

It contains 3 jupyter notebooks to describe our experiments on 3 topics involving SGLD:
  - A Bayesian logistic regression with Laplace prior: experiments on 3 data sets, comparison with other Bayesian methods (Symmetric Adaptative Random Walks and Hamiltonian MCMC coded by ourselves).
  - A shallow bayesian neural network for the same classification task
  - A linear regression model with a comparison of SGLD with SAGA-LD (a version to reduce variance, depicted in Variance Reduction in Stochastic GradientLangevin Dynamics: https://papers.nips.cc/paper/2016/file/9b698eb3105bd82528f23d0c92dedfc0-Paper.pdf).

We highlight results and discuss them in the report.
