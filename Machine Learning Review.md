# 1. Data Visualization
* Matplotlib
* Seaborn
* Plotly
* Missingno

# 2. Data Preprocessing
* Standarization: zero mean and unit variance(height, age, salary)
* Normalization: (0,1)
* Discretization: fixed interval, manual, k-means

# 3. Dimension Reduction
* PCA
    * Full
    * Randomized
    * Kernal
* For images
    * Gradien extraction
    * DAISY bag of features

# 4. Classification
* Linear Regression
    * Loss/Cost function：L(Y,x) = sq(Y-f(x))
    * Minimize Structual Risk function: min(1/n sum(1,n):L(Y,x))
    * Regularization function: control fitting complexity lamda*J(f), prevent overfitting
        * L1(Lasso): sum(abs(x)), weight sparse -> 0, so has feature selection
        * L2(Ridge): sq root of sq sum, weight shrink
    * Object function(both get min): min(1/n sum(1,n):L(Y,x) + lamda*J(f))
* Logistic Regression
* Optimization:
    * Stochastic Gradient Descent
    * Newton's Update Method
    * Hessian
    * Quasi-Newton Methods
        * BFGS
* SVM
* MLP
    * Backpropagation
    * Activation function: relu, sigmoid, tanh(turn linear to non-linear) 0 or 1-> (0,1)
* CNN: Tensorflow and Keras
* RNN

# 5. Validation
* Cross-validation
    * 8/2 split
    * k-fold
