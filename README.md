# support_vector_machine

%------------------------------------ Data --------------------------------------%

Consider the following training data with two categories (labels):

C_1 : 	(1, 3)^T 	(2, 3)^T		(2, 4)^T

C_{-1} :	(3, 1)^T 	(3, 2)^T 	(4, 2)^T

That is, there are six training data points, each data point has two features and a corresponding
label.

%------------------------------------ Goal of the Project --------------------------------------%

We begin by visually examining the data, and determine the hyperplane which separates it. 

Then we find the SVM model by solving the corresponding quadratic programming problem in the dual Lagrangian formulation. The SVM solution ends up being the same as the visual method's hyperplane. 

Lastly, we compare the SVM model with the Linear Discriminant Analysis (LDA) model. The LDA hyperplane ends up being identical to the hyperplane produced from the other methods. 

%------------------------------------ Required Packages --------------------------------------%

	numpy
	
	matplotlib
	
	scipy
	
	quadprog 		(if needed, install it using: pip install quadprog)
