# Neural_Network_Charity_Analysis

# Overview of project

The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
We use the following methods for the analysis:

- Compare the differences between the traditional machine learning classification and regression models and the neural network models.

- Implement neural network models using TensorFlow.

- Preprocess and construct datasets for neural network models.

- Compare the differences between neural network models and deep neural networks.

- Implement deep neural network models using TensorFlow.

# Resources

Data Source: charity_data.csv

Software: Python 3.7, Anaconda Navigator 1.9.12, Jupyter Notebook 6.0.3

# Results

### Data Preprocessing

1. What variable(s) are considered the target(s) for your model?

- Checking to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

2. What variable(s) are considered to be the features for your model?

- The column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively. This variable is then considered as the target for our deep learning neural network.

3. What variable(s) are neither targets nor features, and should be removed from the input data?

 - The columns EIN and NAME are identification information have been removed from the input data to improve code efficiency.

### Compiling, Training, and Evaluating the Model

4. How many neurons, layers, and activation functions did you select for your neural network model, and why?

- This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
The input data has 43 features and 25,724 samples.
The output layer is made of a unique neuron as it is a binary classification.
To speed up the training process, we are using the activation function ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used on the output layer.
- For the compilation, the optimizer is adam and the loss function is binary_crossentropy.

5. Were you able to achieve the target model performance?

- The target for the model was 75%, This is not a satisfying performance to help predict the outcome of the charity donations.

6. What steps did you take to try and increase model performance?

- To increase the performance of the model, we applied bucketing to the feature ASK_AMT and organized the different values by intervals.
We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.
We also tried a different activation function (tanh) but none of these steps helped improve the model's performance.

# Summary

- The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
- Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.









