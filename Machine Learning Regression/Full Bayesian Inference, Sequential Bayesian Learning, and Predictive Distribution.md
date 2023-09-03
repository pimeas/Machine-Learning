# Machine Learning Regression Using Full Bayesian Inference, Sequential Bayesian Learning, and Predictive Distribution

### Part 1: Full Bayesian Inference for Regression
#### Generating the same data from "MAP and Basis Functions.md" and fitting using gaussian basis functions. 
#### Demonstrating the effects of changing the alpha and beta terms with the model dimensionality of 10.


![image](https://github.com/pimeas/Machine-Learning/assets/112512011/8e1b57e6-fb6c-44b7-bde7-31619b9535b9)


##### A lower alpha value with a greater beta value around 0.5 results in a closer fit to the original curve.

![image](https://github.com/pimeas/Machine-Learning/assets/112512011/e5a7df83-ae88-44e0-ae97-7ec8f8c2a71d)

#### Increasing the model dimensionality to 50, results in little change to the prediction because full bayesian inference is minimally dependent on the model complexity.

#### The main difference between full bayesian inference and other bayesian based inference methods, the uncertainty on the parameters are provided. This allows for us to see how changes in the terms affect the model and produce better model predictions

### Part 2: Sequential Bayesian Learning for Regression
#### Fitting the data sequentially 
![IMG_0011](https://github.com/pimeas/Machine-Learning/assets/112512011/80421dc5-ee68-4ddc-a30b-2ecd184910de)


### Part 3: Predictive Distribution for Regression

![image](https://github.com/pimeas/Machine-Learning/assets/112512011/73fbc53a-0142-4dc5-980c-2acef1c2896a)

#### Final predictive distribution graph, with sequential input data. 
#### Predictive Distribution has the ability to incorporate all data points: past and future. It's flexible and less expensive to compute as it gives a distribution that can be updated rather than re-computing the posterior for other methods.
#### The probabilities attained through predictive distribution updates as new data is added to the prediction and additionally provides the uncertainty of the predictions. This is applicable in predicting future data.
