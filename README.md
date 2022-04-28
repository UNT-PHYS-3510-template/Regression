# Regression
This assignment, as the previous one, is based on a data file that was generated in your instructor's research lab. The data file named protein_reduced.csv contains more than 700 rows of data related to the atoms of a small protein (an insulin mutant, entry 1A7F in the Protein Data Bank). For each atom the file report some properties that are related to how close to the surface of the protein the atom is, as well as the distance from the center of mass of the protein.

Assignment 1: Use the linear_regression.ipynb notebook to 
* Perform standardization of the features
* Perform linear regression to predict the distance from the center of mass of the atoms, using each surface or volume descriptor as indipendent variable. For each regression model compute the determination coefficient (R2, or regression score) and select the best feature to predict the label
* For the best model, compute the mean squared error of the fit. 
* For the best model, compute the learning curves for the fit. Split the dataset into training and validation sets and repeat the training as a function of the number of cases in the training set.

Assignment 2: Use the polynomial_regression.ipynb notebook to
* Build polynomial features from a linear feature
* Perform linear regression as a function of the degree of the polynomial and compute the mean squared error for each fit
* Compute the learning curves for the linear, quadratic and order 10 models.
* Use regularization to improve the quality of the fit and avoid overfitting (Ridge or Lasso regression)
