# Hyperparameter-Optimization-with-Monte-Carlo-Training-Set-Data-Sampling

In this notebook we will go through a random search hyperparameter optimization method using a subset of the training dataset. We will use the hyperparameters found and run cross validation on the full training set. We will show that sampling a subset from the training set and using it to find optimal hyperparameters is producing similar results to those using the entire training set. The benefits of using a subset as opposed to the entire training set is time and resources saved: from hours or days to minutes.
We will apply this method to a classification problem.
We will be using XGBoost as our classification algorithm.
