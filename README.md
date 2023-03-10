# Linear-Regression-from-Scratch-EE769-Assignment-1-
## Tasks:
#### 1. Write a function to generate a data matrix X. Inputs: Number of samples, feature dimension. Output: Data matrix X.
#### 2. Write a function to generate dependent variable column t.
###### a) Inputs: Data matrix X, weight vector for each column, bias w0, noise variance
###### b) Output: Target vector t
#### 3. Write a function to compute a linear regression estimate.
###### a) Input: data matrix X and weight vector w 
###### b) Output: y
#### 4. Write a function to compute the mean square error of two vectors y and t.
#### 5. Write a function to estimate the weights of linear regression using pseudo-inverse, assuming L2 regularization:
###### a) Input: X, t, and lambda 
###### b) Output: w, MSE, y
#### 6. Write a function to compute the gradient of MSE with respect to its weight vector.
###### a) Input: X matrix, t vector, and w vector 
###### b) Output: gradient vector
#### 7. Write a function to compute L2 norm of a vector w passed as a numpy array. Exclude bias w0.
#### 8. Write a function to compute the gradient of L2 norm with respect to the weight vectors.
###### a) Input: X matrix and w vector
###### b) Output:gradient vector,where gradient with respect to w0 is 0.
#### 9. Write a function to compute L1 norm of a vector w passed as a numpy array. Exclude bias w0.
#### 10. Write a function to compute the gradient of L1 norm with respect to the weight vectors.
###### a) Input: X matrix and w vector
###### b) Output: gradient vector, where gradient with respect to w0 is 0.
#### 11. Write a function for a single update of weights of linear regression using gradient descent.
###### a) Input: X, t, w, eta, lambda2, lambda1. Note that the weight of MSE will be 1
###### b) Output: updated weight and updated MSE
#### 12. Write a function to estimate the weights of linear regression using gradient descent.
###### a) Inputs: X, t, lambda2(default0), lambda1(default0), eta, max_iter, min_change_NRMSE
###### b) Output: Final w, final RMSE normalized with respect to variance of t.
###### c) Stopping criteria: Either max_iter has been reached, or the normalized RMSE does not change by more than min_change_NRMSE
#### 13. Run multiple experiments(with different random seeds) for, plot the results of (boxplots), and comment on the trends and potential reasons for the following relations:
###### a) Training and validation NRMSE obtained using pseudo inverse with number of training samples
###### b) Training and validation NRMSE obtained using pseudo inverse with number of variables
###### c) Training and validation NRMSE obtained using pseudo inverse with noise variance
###### d) Training and validation NRMSE obtained using pseudo inverse with w0
###### e) Training and validation NRMSE obtained using pseudo inverse with lambda2
###### f) time taken to solve pseudo inverse with number of samples and number of variables and its breaking points
###### g) Training and validation NRMSE obtained using gradient descent with max_iter
###### h) Training and validation NRMSE obtained using gradient descent with eta
###### i) time taken to solve gradient descent with number of samples and number of variables and its breaking points
###### j) time taken to solve gradient descent with number of variables and its breaking point
###### k) Training and validation NRMSE and number of nearly zero weights obtained using gradient descent with lambda2
###### l) Training and validation NRMSE and number of nearly zero weights obtained using gradient descent with lambda1
###### m) Training and validation NRMSE for optimal lambda2 with noise variance
###### n) Training and validation NRMSE for optimal lambda1 with noise variance
###### o) Experiment (f) but, this time with number of training samples and number of variables
#### 14. Write your overall learning points by doing entire assignment
#### 15. Quote your references, including roll numbers of fellow students with whom you discussed. Be specific about which part was inspired by what source or which friend.
