# Machine Learning Classification Using Predictive Distribution and Gaussian Processes

### Part 1: Predictive Distribution
#### Generating clustered data.
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/5389a066-030c-42ce-928e-a553cae49b91)
#### Implementing predictive distribution with an output classifying the data point as belonging to the first or second cluster.
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/05153e85-8a17-4de2-a5fc-82f12b3dcd82)

#### With this probability map, a user can input a data point and the classification, probability of the classification, and uncertainty of the classification is returned. 

### Part 2: Gaussian Processes
#### Generating clustered data with two classes. 
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/3ef4198f-db6a-4693-b2d8-7c5ece477e03)

#### Using a kernel to draw a probability map with Gaussian Processes
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/d194b6e2-24ca-4e14-8cea-230cb0316c33)

#### With data where a cluster is located within a larger cluster of data, the probability map is constructed as follows:
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/1fe4ef24-5332-4790-9d63-b73066764f3a)
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/35078081-d9e5-4486-a747-05d81b4d9ec8)

#### With data where a cluster is located between two clusters of the same class, the probability map is constructed as follows:
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/81fc7e30-e7af-43de-8465-7f8a714dc5a1)
![image](https://github.com/pimeas/Machine-Learning-Classification/assets/112512011/cf4eea05-a603-4202-ab00-100eefb3b334)
