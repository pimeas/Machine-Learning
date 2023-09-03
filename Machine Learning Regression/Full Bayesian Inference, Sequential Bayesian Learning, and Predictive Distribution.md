# Machine Learning Regression Using Full Bayesian Inference, Sequential Bayesian Learning, and Predictive Distribution

### Part 1: Full Bayesian Inference for Regression
#### Generating the same data from "MAP and Basis Functions.md" and fitting using gaussian basis functions. 
#### Demonstrating the effects of changing the alpha and beta terms with the model dimensionality of 10.
![Screen Shot 2023-09-03 at 3 15 03 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/0e2c3955-a69b-4289-b5b3-7b8830365f66)
##### A lower alpha value with a greater beta value around 0.5 results in a closer fit to the original curve.
![Screen Shot 2023-09-03 at 3 19 19 PM](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/88610578-f467-4b72-88ef-59a83ad7c072)
#### Increasing the model dimensionality to 50, results in little change to the prediction because full bayesian inference is minimally dependent on the model complexity.

#### The main difference between full bayesian inference and other bayesian based inference methods, the uncertainty on the parameters are provided. This allows for us to see how changes in the terms affect the model and produce better model predictions

### Part 2: Sequential Bayesian Learning for Regression
#### Fitting the data sequentially 
![IMG_0011](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/8ce51b56-ef15-4bfe-90d8-9fdc00cc77d0)

### Part 3: Predictive Distribution for Regression
![download (6)](https://github.com/sammycpark/Machine-Learning-Regression/assets/112512011/9e4bce18-c6c3-4d44-86f9-26df29021a50)
#### Final predictive distribution graph, with sequential input data. 
#### Predictive Distribution has the ability to incorporate all data points: past and future. It's flexible and less expensive to compute as it gives a distribution that can be updated rather than re-computing the posterior for other methods.
#### The probabilities attained through predictive distribution updates as new data is added to the prediction and additionally provides the uncertainty of the predictions. This is applicable in predicting future data.
