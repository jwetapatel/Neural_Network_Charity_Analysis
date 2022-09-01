# Neural_Network_Charity_Analysis

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







