# Machine Learning Regression using Maximum A Posteriori (MAP) and Basis Functions

### Part 1: MAP for Regression
#### Generating 2D data points with noise using a sine function.
![image](https://github.com/pimeas/Machine-Learning/assets/112512011/36647229-b8da-4f31-baf7-f4fcd0006626)


#### Fitting the generated data using MAP and demonstrating the effects of changing the coefficient of the regularization and prior term.
![image](https://github.com/pimeas/Machine-Learning/assets/112512011/61dfbad8-cc72-44f2-a5ac-404a63bb7505)

##### Changing these two values affect the fitting accuracy. Greater model complexity (M) results in overfitting, while simple models, like cubic, is underfitting. However, having a nonzero regularization term (alpha) reduces overfitting.

### Part 2: Basis Functions for Regression
#### Using the same data points generated in part 1, Gaussian basis functions and sigmoid basis functions are employed.
##### Gaussian basis functions at different values of M
![image](https://github.com/pimeas/Machine-Learning/assets/112512011/bcb1b032-15b9-4515-8db4-8eb39fbaf50f)

##### Sigmoid basis functions at different values of M
![image](https://github.com/pimeas/Machine-Learning/assets/112512011/6cb17f42-74ee-4aa1-8e8a-ab915f3bd6ac)

#### Compared to regression models that predict using polynomial functions, basis functions have the advantage of being simpler in its implementation for increasingly complex models. The greater the model complexity/dimensionality, the larger the input data values will be as they will be powered to whatever the power of the function is. Larger data values mean that the model parameters have to be very small to accommodate for the very large number. This creates difficulties in the implementation of polynomial functions.
