# Machine Learning Regression using Maximum A Posteriori (MAP) and Basis Functions

### Part 1: MAP for Regression
#### Generating 2D data points with noise using a sine function.
![Screen Shot 2023-09-03 at 2 37 37 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/168d6619-80ba-4052-9ef7-2c0b55ae256b)

#### Fitting the generated data using MAP and demonstrating the effects of changing the coefficient of the regularization and prior term.
![Screen Shot 2023-09-03 at 2 42 53 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/285131ab-749b-4855-a1cf-abdbc41f9dba)
![Screen Shot 2023-09-03 at 2 43 09 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/7306522f-528e-4bdd-a6d9-a64a04bb61db)
##### Changing these two values affect the fitting accuracy. Greater model complexity (M) results in overfitting, while simple models, like cubic, is underfitting. However, having a nonzero regularization term (alpha) reduces overfitting.

### Part 2: Basis Functions for Regression
#### Using the same data points generated in part 1, Gaussian basis functions and sigmoid basis functions are employed.
##### Gaussian basis functions at different values of M
![Screen Shot 2023-09-03 at 2 49 30 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/b7e08599-3bb4-4ba1-b446-e7a5e74e6c7b)

##### Sigmoid basis functions at different values of M
![Screen Shot 2023-09-03 at 2 49 39 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/f29ec827-d22c-4bfd-a0d0-9a2cde00e279)

#### Compared to regression models that predict using polynomial functions, basis functions have the advantage of being simpler in its implementation for increasingly complex models. The greater the model complexity/dimensionality, the larger the input data values will be as they will be powered to whatever the power of the function is. Larger data values mean that the model parameters have to be very small to accommodate for the very large number. This creates difficulties in the implementation of polynomial functions.
