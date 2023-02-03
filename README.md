# Data-Quality-and-Model-Drift
Data quality is an essential part of the data strategy. It is initially considered in the design of raw datasets/databases. We focus on the dimensions relevant to Machine Learning
A model drift can occur when there is a significant performance change of the model over time. To understand more about model drift in the campaign response problem, we need to build a drift detection dashboard and use all data prior to Dec 2013 (inclusive) to train a model. Then this model is put in production, to calculate scores for all clients after Jan-2014 (inclusive).
Identified top 5 features that contributed to model drift using Jensen-Shannon divergence method.
This project is coded in python
